# Problem 2 - Decomposition

Consider the following table:

|fourm_name|popularity|post_id|title|article|reply|
|---|---|---|---|---|---|
|Gossiping|100|132|Girlfriend|How can I get girlfriend ?|["Haha", "I don't know"]
|Gossiping|100|251|Firends|I don't have a friend...|["Haha", "I can be", "QQ"]
|Joke|23|41|Knock|Knock! Knock! ...|["Then?", "What's the point ?"]
|Joke|23|156|Santa Claus|Hold! Hold! Hold!|["XDD"]

This table is not in the 3rd normal form.

Here are its funtional dependencies:
- fourm_name -> popularity
- {fourm_name, post_id} -> {title, article, reply}

Please decompose the table for **the 3rd normal form**. You may add new fields to preserve the relationships. (40 points)

[1]: https://www.postgresql.org/docs/9.2/static/datatype.html
