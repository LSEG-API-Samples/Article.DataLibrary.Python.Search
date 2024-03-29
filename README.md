# Building Search into your Application Workflow

For the equivalent .Net implementation, refer here: [Article.DataLibrary.DotNet.Search](https://github.com/Refinitiv-API-Samples/Article.DataLibrary.DotNet.Search)


## <a id="overview"></a>Overview
With the wealth of content offered within the Refinitiv ecosystem, the following series of examples will outline the core capabilities available within Refinitiv's Search API, a powerful, Google-like search engine covering content such as quotes, instruments, organizations, and many other assets that can be programmatically integrated within your business Workflow.

Details and concepts are further explained in the [Building Search into your Application Workflow](https://developers.refinitiv.com/en/article-catalog/article/building-search-into-your-application-workflow) article published on the [Refinitiv Developer Community portal](https://developers.refinitiv.com).

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

License(s):

- A Refinitiv desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 


[Development Environment](https://developers.refinitiv.com/en/api-catalog/eikon/eikon-data-api/tutorials#setting-up-a-python-development-environment)

- Tested with Python 3.9.4
- Packages: [rdp](https://pypi.org/project/refinitiv-dataplatform/) [pandas](https://pypi.org/project/pandas/) datetime dateutil
- RD Library for Python installation:  '**pip install refinitiv-data**'

## <a name="setup"></a>Setup

The application package includes a series of Jupyter Notebooks demonstrating features of the service.  Depending where you plan to access the content from, you will need provide the proper credentials:
* **Desktop Access**
  
  The notebooks have been set up and tested to access data within the desktop, whether Refinitiv Workspace or Eikon.  For each, you simply need to replace the **'Your API Key here'** with your own [generated application API key](https://developers.refinitiv.com/en/api-catalog/eikon/eikon-data-api/quick-start#quick-start-guide-for-windows).
  
* <a id="authors"></a>Authors

* **Nick Zincone** - Release 1.0.  *Initial version*
* **Nick Zincone** - Release 1.1.  *Updated to reflect new RD Library release*



