<h1 align="center"> Data Anlaysis of the Rolling Stone Top 500 Albums Ranking </h1>

## This Analysis has the objective to see how the data were distributed along the dataset.

## <strong> Overview </strong>
The dataset is from Kaggle and can be accessed <a href="https://www.kaggle.com/datasets/umerhaddii/rolling-stone-album-rankings"> here </a>. 
<br>
<br>
The RS 500 list is a product of meticulous selection by Rolling Stone's editors, who drew upon the insights from two comprehensive surveys. Initially, in 2003, a diverse panel comprising 271 notable figures from the music industry, including artists, producers, and journalists, was tasked with identifying the most influential albums ever produced. Subsequently, in 2009, a similar assembly of 100 specialists was convened to determine the standout albums of the 2000s. The outcomes of these polls were instrumental in shaping Rolling Stone's esteemed compilation of the all-time greatest albums. The dataset contains details information of The Pudding compares Rolling Stone’s “500 Greatest Albums of All Time” lists from 2003, 2012, and 2020.

## <strong> Python libraries </strong>
* Matplotlib;
* Pandas; 
* Seaborn.

## <strong> Methodology </strong>
1. **Data Collection**: Gathering the RS 500 ranking from Kaggle.
2. **Data Cleaning**: Handling missing values, duplicates, outliers and ensuring data consistency.
3. **Data Analysis**: Conducting statistical analysis and generating visualizations.
4. **Interpretation**: Drawing insights from the visualizations and statistical results.

## <strong> Results </strong>
#### Trend Analysis of the 20 best Albums Over Time (2003 rank until 2020 rank)
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/6837803c-4626-49cf-ac32-5baac98563e1)
**Description**: It is possible to see that some albums, even after many years, still remain highly rated as the best (within the top 50), likely evaluated by different professionals over time, which shows that they have proven their quality and excellence over the years. Only a small minority has experienced a sharp decline in ratings in recent years compared to earlier ones.

#### Genre Popularity Visualization
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/c42cbce2-3576-48b5-bcb3-0f89cdad5f03)
**Description**: It can be observed that there is a wide distribution of musical genres among the albums.
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/402ebdc6-e789-4634-90dc-9aecbb3d221b)
**Description**: In this graph, we can already see that musical genres have significant fluctuations over the years. This can be attributed to various factors, such as the most listened-to styles at the time, popular taste, among others.

#### Artist Analysis
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/a6266813-2a25-42af-810d-ee7085d895db)
**Description**: Here, it is possible to see which artists appear most frequently in this list of 500 albums.

#### Album Release Year Analysis
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/bec0fc5f-04ce-4bb4-a4b7-b52e81cda39c)
**Description**: It can also be seen that there is a significant fluctuation in the release years of the albums that make up this list.
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/90524ad9-d114-40c4-a200-3efa9a1ccb15)
**Description**: We can see that in the division of album counts by decade, the 70s is the period where the most albums in this list were released.
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/0308e945-374a-4112-b4d8-180f93803c1c) <br>
**Description**: Now, subsequently, the proportion of albums by decade.

#### Billboard Performance vs. RS Rankings
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/5dfdd619-429c-4ab6-979f-7c3fc96ce26b)
**Description**: In this visualization, we can see the top 15 albums that reached the top of the Billboard charts.

#### Spotify Popularity Analysis
![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/8119f7c5-6e8f-49b2-85e3-337f0f8ddaa6)
**Description**: Next, we have the analysis of the 10 most popular albums on Spotify (which are from a more recent period).

![image](https://github.com/arthurcassemiroo/Data-analysis-RS500/assets/88465565/81155287-e2ee-4426-b93c-dd593ab582e1)
**Description**: With this, a study was conducted on the correlation between Spotify popularity and the ranking of the 500 albums to determine if there is necessarily a connection between the two. With a correlation of 0.009277547787263975, it indicates that there is virtually no linear relationship between Spotify Popularity and RS 500 Ranking.
