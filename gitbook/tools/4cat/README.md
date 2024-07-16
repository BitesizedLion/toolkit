---
description: >-
  4CAT is a tool designed for the easy collection and analysis of online
  datasets, facilitating researchers and analysts in uncovering patterns and
  trends in social media and other digital platforms.
---

# 4CAT

## URL

[https://4cat.nl/](https://4cat.nl/)

## Description

4CAT is a containerised [Docker](https://www.docker.com/) application that can be installed on a server to create an accessible web-based tool that enables users to gather and analyze online data efficiently. It supports researchers and analysts by providing a streamlined way to explore and identify trends within data from social media and other digital platforms. The tool is structured to accommodate a variety of online datasets, making it versatile for different research needs. By offering capabilities to collect, process, and examine digital content, 4CAT stands as a valuable resource for those looking to conduct comprehensive studies on the dynamics of online communities and the dissemination of information across virtual networks.

Although the tool's installation requires technical knowledge once installed the application can be used by as team as a normal web application.&#x20;

**Features:**

_**Data Sources**_

* **Data sources (actively supported)**: _4chan, Telegram, Tumblr_
* **Data sources (additional support through Zeeschuimer)**: _TikTok (posts and comments), Instagram (posts only), Twitter, LinkedIn, 9gag, Imgur, Douyin, Gab_
* **Data sources (additional support)**: _Facebook and Instagram_ (via CrowdTangle or Facepager exports), _YouTube_ videos and comments (via the YouTube Data Tools), _Weibo_ (via Bazhuayu)
* **Scheduling:** once data sources are configured a scheduler can be set up to regularly import data from a data source.

_**Processors**_

* **Combined:** across the data sources there are a series of combined processors that for common processing tasks e.g. annotate images with Google Vision API, histogram with the number of posts per month.
* **Conversion:** convert date source output file formats e.g. CSV, JSON, NDJSON, etc.
* **Cross Platform:** download YouTube thumbnails.
* **Filtering:** filter by value, date, words or phrases and support for processing tasks like anonymise datasets.
* **Networks:** analyse and output datasets for network visualisation in various GEXF formats.
* **Post metrics:** visualise and export various metrics including **c**ounts of values, posts, Hatebase analysis, Extract Text from Images, Extract YouTube metadata
* **Text Analysis:** various text analysis processors including extracting named entities, generating topic models, word counts, etc.
* **Thread metrics:** debate metrics.
* **Visual:** including histogram, download images, word trees and clouds, image walls.

Example below shows creating a new dataset and customising the visualis&#x20;

In the example below, Tumblr is selected to get posts and comments from Tumblr. In this case, the main way to collect data is through tags, which can be inserted in the Tags/blogs: field. In this case, we will search for posts with the tag #liminal spaces:

<figure><img src="https://lh7-us.googleusercontent.com/iEJanp6kHwwHU7RW7A9eYfTC3N6hBkdvZz5AUyBYE8yDyHUgfGeKS6KuqxaOLT0GF1Dg_bSSVQipQtb6_K4jX2bVpxXGfCQ-RRwq_nL5mil3COBxkOBWou14ETrr0XFQILrbko-g3TkFMumnDTjCx-o" alt="Screenshot of 4Cat create new dataset screen shows the input fields require to create a Tumblr dataset."><figcaption><p>Screenshot of 4Cat create new dataset screen.</p></figcaption></figure>

Example of the customisation of a steam graph visualisation in 4Cat.

<figure><img src="https://lh7-us.googleusercontent.com/qjR2UY8Xbt_M-Vb4DiRJZJcWhBtaeXgdekAo_Bl6eeYvJoGlZ7sFczznJDuxXnDkX1c2PvPCYhNh4qnbY0Xa6F6IjFmM8aCNQEp6laPkT4RTICZ90GwocoJ-bOwW9m2YDHqA82bo3lneCdNhair9Fw" alt=""><figcaption><p>screenshot of steam graph customisation screen. </p></figcaption></figure>

4Cat, once installed, is available in the following formats:

* Web

Latest changes: [https://github.com/digitalmethodsinitiative/4cat/releases](https://github.com/digitalmethodsinitiative/4cat/releases)

## Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

Hosting cost may apply if 4Cat is deployed as a web application for a team.

## Level of difficulty

<table><thead><tr><th data-type="rating" data-max="5"></th></tr></thead><tbody><tr><td>5</td></tr></tbody></table>

## Requirements

* **Platforms**: runs on Linux, Windows and macOS.
* **Docker:** the application has been containerised with [Docker](https://www.docker.com/) so Docker needs installed for the application to run.
* **Memory Requirements:** 16GB of RAM
* **API key**: Some of the custom datasets may require and API key to be configured.

For more information on hardware requirements see: [https://github.com/digitalmethodsinitiative/4cat/wiki/What-hardware-do-I-need-to-run-4CAT%3F](https://github.com/digitalmethodsinitiative/4cat/wiki/What-hardware-do-I-need-to-run-4CAT%3F)&#x20;

## Limitations

* **Technical Installation:** the primary limitation of 4Cat is that to install it you need specialised technical knowledge of tools like [Docker](https://www.docker.com/) and a server to run it on.    &#x20;
* **Data Access:** 4CAT may have limitations in terms of the range and depth of data it can access from certain platforms due to API restrictions or changes in platform policies.
* **Complex Queries:** Users with limited technical expertise may find it challenging to construct complex queries or fully utilize the tool's capabilities without a steep learning curve.
* **Processing Time:** Large datasets or complex analysis tasks may require significant processing time, which could impact efficiency for time-sensitive research.
* **Update Frequency:** The tool’s ability to keep pace with rapid changes in social media platforms and internet technology may be limited, potentially affecting its long-term utility.
* **Cost:** While 4CAT itself may be free to use, significant analyses might require substantial computational resources or access to premium data sources, incurring potential costs.
* **Rate Limits:** some of the services that the datasets are gathered from may have rate limits. &#x20;

## Ethical Considerations

When using 4CAT for research, several ethical considerations must be taken into account:

* **Privacy and Consent:** Researchers must navigate the complex landscape of user privacy, especially when collecting data from social media platforms. It is crucial to ensure that data collection complies with the privacy policies of the platforms and respects the consent of the users, especially in cases where users have not explicitly agreed to share their data for research purposes.
* **Data Anonymization:** Ensuring that data is anonymized to protect the identities of individuals is paramount. This involves removing or obfuscating any identifiable information before analysis or publication of the research findings.
* **Bias and Representation:** The tool's dependence on accessible data from platforms may introduce bias, given that not all voices and perspectives are equally represented online. Researchers should be aware of these limitations and consider them when drawing conclusions from their data.
* **Impact on Subjects:** There should be careful consideration of the potential impact of the research on the subjects being studied, especially if the findings could negatively affect them or the communities they belong to.
* **Compliance with Legal Standards:** Ensuring compliance with applicable laws and regulations, such as GDPR in the European Union, is essential. Researchers must be mindful of the legal implications of data collection, storage, and analysis practices.

By addressing these ethical considerations, researchers can foster responsible use of 4CAT and contribute positively to the broader knowledge base without infringing on the rights or well-being of individuals or communities.

## Guides and articles

To effectively use 4Cat, especially for beginners or those looking to refine their skills, the following resources are highly recommended:

**Official Wiki**&#x20;

* [https://github.com/digitalmethodsinitiative/4cat/wiki](https://github.com/digitalmethodsinitiative/4cat/wiki)
* [https://computationalcommunication.org/ccr/article/view/120](https://computationalcommunication.org/ccr/article/view/120)

**Tutorials and Articles**

* _4CAT exercises_ (no date) _Google Docs_. Available at: [https://docs.google.com/document/d/1po-sOB8tDRZlvWrEayu97cGh\_qsBuW0URd4md0\_tv7k/edit?usp=embed\_facebook](https://docs.google.com/document/d/1po-sOB8tDRZlvWrEayu97cGh\_qsBuW0URd4md0\_tv7k/edit?usp=embed\_facebook) (Accessed: 12 May 2024).
* ‘CAT4SMR – Capture and Anaysis Tools for Social Media Research’ (no date). Available at: [https://cat4smr.humanities.uva.nl/](https://cat4smr.humanities.uva.nl/) (Accessed: 13 May 2024).Peeters, S. and Hagen, S. (2022) ‘The 4CAT Capture and Analysis Toolkit: A Modular Tool for Transparent and Traceable Social Media Research’, _Computational Communication Research_, 4(2), pp. 571–589.
* _"As a researcher, this tool saves me a lot of work and stress” - News - Utrecht University_ (2023). Available at: [https://www.uu.nl/en/news/as-a-researcher-this-tool-saves-me-a-lot-of-work-and-stress](https://www.uu.nl/en/news/as-a-researcher-this-tool-saves-me-a-lot-of-work-and-stress) (Accessed: 13 May 2024).

#### Video Tutorials

* _4CAT Tutorial - Creating a Dataset - YouTube_ (no date). Available at: [https://www.youtube.com/watch?v=VZH9SQM3dmI\&list=PLWukutaRyIn31H0uPfkYlmbWvo83PnXXo\&index=2](https://www.youtube.com/watch?v=VZH9SQM3dmI\&list=PLWukutaRyIn31H0uPfkYlmbWvo83PnXXo\&index=2) (Accessed: 13 May 2024).
* _4CAT Tutorial: Analysing a dataset using processors_ (2021). Available at: [https://www.youtube.com/watch?v=XIpGt3uzqNQ](https://www.youtube.com/watch?v=XIpGt3uzqNQ) (Accessed: 13 May 2024).
* _4CAT Tutorial: Installing via Docker - YouTube_ (no date). Available at: [https://www.youtube.com/watch?v=oWsB7bvNfOY\&list=PLWukutaRyIn31H0uPfkYlmbWvo83PnXXo\&index=4](https://www.youtube.com/watch?v=oWsB7bvNfOY\&list=PLWukutaRyIn31H0uPfkYlmbWvo83PnXXo\&index=4) (Accessed: 13 May 2024).

#### Developer Resources

* [https://github.com/digitalmethodsinitiative/4cat](https://github.com/digitalmethodsinitiative/4cat)

**Community and Support**

* [https://www.facebook.com/groups/678943026381479](https://www.facebook.com/groups/678943026381479)

By utilizing these resources, users can enhance their 4Cat experience, whether for personal navigation, planning trips, or developing custom mapping

## Tool provider

Digital Methods Initiative [https://digitalmethods.net/](https://digitalmethods.net/) - Amsterdam

## Advertising Trackers

* [x] This tool has not been checked for advertising trackers yet.
* [ ] This tool uses tracking cookies. Use with caution.
* [ ] This tool does not appear to use tracking cookies.

| Page maintainer                      |
| ------------------------------------ |
| Bellingcat Volunteer Team/Unassigned |
|                                      |
