# Note
-----
This dataset is referring expression dataset constructed from Twitter. The dataset is consisted of unanswerable data whose entities cannot be grounded to the images, and answerable one.

# Data Property Description
---
The Data properties contain `tweet_url`, `tweet_id`, `text`, `image_properties`, `category`, `split`, `entities`.

`tweet_url`: The Twitter URL of data.
`tweet_id`:  The ID of the Twitter.
`text`: the content of the Tweet.
`image_properties`: the image properties of the Tweet.
`category`: the category of data. The categories of dataset are same as REFCOCO'ones.
`entities`: the entities have child properties as following.

* `sent_row`: the sentence that the entity belongs to.
* `sent_id`: the sentence ID.
* `refs`: the refs have child properties as following.
	- `ref_row`: the text of the referring expression.
	- `ref_id`: the referring expression ID.
	- `ref_pos`: the position of the referring expression in the sentence.
	- `bounding_boxes`: the coordinate of the bounding box `(height, left, top, width)`
	- `answerable`: the boolean value of weather the referring expression is answerable or not.

# Citation
---
If you used this dataset, that were collected by ~, please consider cite our paper


