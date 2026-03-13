# Building Search into your Application Workflow

For the equivalent .Net implementation, refer here: [Article.DataLibrary.DotNet.Search](https://github.com/LSEG-API-Samples/Article.DataLibrary.DotNet.Search)


## <a id="overview"></a>Overview
With the wealth of content offered within the LSEG ecosystem, the following series of examples will outline the core capabilities available within LSEG's Search API, a powerful, Google-like search engine covering content such as quotes, instruments, organizations, and many other assets that can be programmatically integrated within your business Workflow.

Details and concepts are further explained in the [Building Search into your Application Workflow](https://developers.lseg.com/en/article-catalog/article/building-search-into-your-application-workflow) article published on the [LSEG Developer Community portal](https://developers.lseg.com).

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by LSEG only for the purpose of illustrating the concepts of creating example scenarios using the LSEG Data Library for Python.

***Note:** To [ask questions](https://community.developers.lseg.com/index.html) and benefit from the learning material, I recommend you to register on the [LSEG Developer Community](https://developers.lseg.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

License(s):

- An LSEG Workspace desktop license that has API access 


[Development Environment](https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/tutorials#setting-up-a-python-development-environment)

- Tested with Python 3.12.14
- Packages: [ld](https://pypi.org/project/lseg-data/) [pandas](https://pypi.org/project/pandas/) datetime dateutil
- LSEG Data Library for Python installation:  '**pip install lseg-data**'

## <a name="setup"></a>Setup

The application package includes a series of Jupyter Notebooks demonstrating features of the service.  Depending where you plan to access the content from, you will need provide the proper credentials:
* **Desktop Access**
  
  The notebooks have been set up and tested to access data within the LSEG Workspace desktop application.  For each, you simply need to replace the **'Your API Key here'** with your own [generated application API key](https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/quick-start#quick-start-guide-for-windows).
  
* <a id="authors"></a>Authors

* **Nick Zincone** - Release 1.0.  *Initial version*
* **Nick Zincone** - Release 1.1.  *Updated to reflect new RD Library release*
* **Nick Zincone** - Release 1.2.  *Updated to reflect new LSEG Data Library release*



