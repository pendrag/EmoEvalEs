# EmoEvalEs

Files are encrypted and password-protected. Participants of the [EmoEvalEs](https://competitions.codalab.org/competitions/28682) task at IberLEF will be notified through Codalab competition's forum with the password to gain access to data.

Files:

* **dev.tsv** (in **emoevales_zip**): tab separated `id` `event` `tweet` `offensive` `emotion`
  - `id`: It is the ID of the comment (you have to use it in your submission)
  - `event`: Hashtag associated to the tweet. There are a limited set of "events" in the dataset
  - `offensive`: Additional label (flag YES/NO) specifying whether the tweet was considered offensive according to at least two human annotators.
  - `emotion`: Emotion label. One of 'anger', 'disgust', 'fear', 'joy', 'sadness', 'surprise' or 'others'.
