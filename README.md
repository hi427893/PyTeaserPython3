# PyTeaserPython3

A fork of [PyTeaser](https://github.com/xiaoxu193/PyTeaser) updated to work in Python 3.

See [Text Summarization in Python](https://rare-technologies.com/text-summarization-in-python-extractive-vs-abstractive-techniques-revisited/) for more details on the algorithm.


# Usage:
## sample command:
```Python
>>> from pyteaser import SummarizeUrl
>>> url = 'http://www.huffingtonpost.com/2013/11/22/twitter-forward-secrecy_n_4326599.html'
>>> summaries = SummarizeUrl(url)
>>> print(summaries)

```

## output
```
["Twitter's move is the latest response from U.S. Internet firms following disclosures by former spy agency contractor Edward Snowden about widespread, classified U.S. government surveillance programs.", '"Since then, it has become clearer and clearer how important that step was to protecting our users\' privacy."', '"A year and a half ago, Twitter was first served completely over HTTPS," the company said in a blog posting.', 'The online messaging service, which began scrambling communications in 2011 using traditional HTTPS encryption, said on Friday it has added an advanced layer of protection for HTTPS known as "forward secrecy."', '(Reuters) - Twitter Inc said it has implemented a security technology that makes it harder to spy on its users and called on other Internet firms to do the same, as Web providers look to thwart spying by government intelligence agencies.']
```

