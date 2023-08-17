# Exploring Hacker News Posts

This project involves an exploration and analysis of two types of posts from [Hacker News](https://news.ycombinator.com/): `Ask HN` and `Show HN`. The goal is to compare these post types and identify patterns in terms of comments received and the best time for post creation.

## Overview

Hacker News is a popular platform for sharing and discussing tech-related content. Users can submit posts to ask questions (`Ask HN`) or showcase projects/news (`Show HN`). In this project, we analyze the following aspects:

- Do `Ask HN` or `Show HN` posts receive more comments on average?
- Is there a specific time window when `Ask HN` posts tend to receive more comments?

## Data

The project uses a dataset containing a subset of Hacker News posts. The dataset has been filtered to include only posts with comments. Each post's attributes include ID, title, URL, points, comments count, author, and creation timestamp.

## Analysis Steps

1. Data Loading: The dataset is loaded from a CSV file, and headers are removed.
2. Categorizing Posts: Posts are categorized as `Ask HN`, `Show HN`, or others based on their titles.
3. Comments Analysis: We calculate the average number of comments for `Ask HN` and `Show HN` posts.
4. Time Analysis: We analyze the number of `Ask HN` posts and comments by hour of creation.
5. Average Comments by Hour: The average comments for `Ask HN` posts are calculated for each hour.
6. Results: The hours with the highest average comments are highlighted.

## Conclusion

Based on the analysis, it's recommended to create `Ask HN` posts during the 15:00 - 16:00 (3:00 pm - 4:00 pm EST) time window to maximize engagement. These posts tend to receive the highest average comments during this period. Overall, this project provides insights into user engagement on Hacker News and showcases the power of data analysis in identifying trends.

## Getting Started

To explore the analysis process and findings, take a look at the Jupyter Notebook [here](notebooks/Exploring_Hacker_News_Posts.ipynb).

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any enhancements or suggestions.

## License

This project is licensed under the [MIT License](LICENSE).