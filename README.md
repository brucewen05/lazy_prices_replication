
This report builds upon the seminal work [Lazy Prices](https://github.com/brucewen05/lazy_prices_replication/blob/main/lazy_prices.pdf) by Cohen, Malloy, and Nguyen, which investigates the extent of investor inattention to textual changes in corporate 10-K and 10-Q filings. Contrary to the prevailing view that financial disclosures have lost their informational value, the study shows that even subtle changes in the language of these reports can be powerful predictors of future firm performance. This report includes implementations that replicate the findings of the original paper, along with several enhancements we introduced.

The following resources are provided:

- lazy_price similarity calculation.ipynb: Contains the logic for calculating textual similarity in the filings.
- Data Preparation for lazy_price_replication.ipynb: Provides the workflow for data preparation, including sentiment scores, stock prices, and other relevant data.
- Fama-French.ipynb: Contains the portfolio construction logic, as well as the methodology for validating alpha.
- draw_graphs.ipynb: Includes the code for generating graphs and visualizations.
- Additionally, the prepared datasets can be accessed via this [Google Drive link](https://drive.google.com/file/d/1IW6Ea2i8D6ZbyAx9xoPCYxmxDG1gUUGW/view?usp=sharing).