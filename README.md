# Video-Game-Sales

https://www.kaggle.com/gregorut/videogamesales Data

In the vg-stats notebook answer the following questions/do the following tasks. Note that the numbers quoted for sales are in the millions, and apply only for those games with over 10,000 sales.:

- Which company is the most common video game publisher?
- What’s the most common platform?
- What about the most common genre?
- What are the top 20 highest grossing games?
- For North American video game sales, what’s the median?
    - Provide a secondary output showing ten games surrounding the median sales output
    - assume that games with same median value are sorted in descending order
- For the top-selling game of all time, how many standard deviations above/below the mean are its sales for North America?
- The Nintendo Wii seems to have outdone itself with games. How does its average number of sales compare with all of the other platforms?
- Come up with 3 more questions that can be answered with this data set.


User Acceptance Tests

Below are example tests. You’ll need one test minimum for each requirement listed above.
```python
def test():

    def assert_equal(actual,expected):
        assert actual == expected, f"Expected {expected} but got {actual}"

    assert_equal(most_common_publisher, None)
    assert_equal(most_common_platform, None)
    assert_equal(most_common_genre, None)
    assert_equal(top_twenty_highest_grossing_games.iloc[0].Name, None)
    assert_equal(top_twenty_highest_grossing_games.iloc[19].Name, None)
    assert_equal(na_median_sales, None)
    assert_equal(ten_median_na_seller_names, None)

    print("Success!!!")

test()
```
