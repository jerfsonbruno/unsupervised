Unsupervised
=====================

Examples of applying unsupervised machine learning using K-means clustering.

## Colors

Unsupervised learning is applied to a data set of randomly generated colors. The red, green, and blue values are used as features to categorize each color under a specific parent category.

For example, purple might be categories as Red or Blue. Likewise, Sky Blue would be categorized under Blue.

### Cluster Categories

- Red
- Green
- Blue

### Results

The following graphs show the results of clustering and categorizing colors by their red, green, and blue values.

#### 1,000 Randomly Generated Colors

!(1,000 Randomly Generated Colors)[/images/plot0.png]

#### 100 Randomly Generated Colors

!(100 Randomly Generated Colors)[/images/plot1.png]

#### 3 Detected Clusters Within Colors

!(3 Detected Clusters Within Colors)[/images/plot2.png]

#### Assigning Colors to a Cluster

!(Assigning Colors to a Cluster)[/images/plot3.png]

#### Viewing Colors Within Their Cluster

!(Viewing Colors Within Their Cluster)[/images/plot4.png]

#### Predicting the Category for New Colors

!(Predicting the Category for New Colors)[/images/plot5.png]

## Exchange Traded Stock and Bond Funds (ETF)

Unsupervised learning is applied to a data set of exchange traded funds. The percentage values for "Year to Date", "1 Year", "5 Year", and "10 Year" returns are used as features to categorize each ETF under a specific parent category.

### Cluster Categories

- International
- StockBigGain
- Stock
- Bond
- SmallMidLargeCap

### Results

The following output shows the results of clustering and categorizing ETF funds based on their percentage returns.

#### Training Set Category Results

[Results](/results/train.csv)

#### Test Set Category Results

[Results](/results/test.csv)

## License

MIT

## Author

Kory Becker

http://www.primaryobjects.com/kory-becker
