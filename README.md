# Science fake news on Facebook

This analysis consists of two parts. First, on [scrape-media-bias.ipynb](scrape-media-bias.ipynb), it will scrape the [Media Bias/Fact Check](https://mediabiasfactcheck.com/) lists of websites tagged as "least biased", "conspiracy-pseudoscience" and "pro-science". After gathering the list, it will go through each of these sites to gather their Facebook pages URLs and generate a list compatible with [CrowdTangle](https://www.crowdtangle.com/).

Finally, on [analysis.ipynb](analysis.ipynb), CrowdTangle data for Facebook posts on these groups of pages will be analysed and compared.

## License

This software is distributed under the [MIT license](LICENSE).