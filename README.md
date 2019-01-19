# CCP
A central counterparty clearing house (CCP) is an organization that exists in various European countries to help facilitate trading done in European derivatives and equities markets. These clearing houses are often operated by the major banks in the country to provide efficiency and stability to the financial markets in which they operate. 

This app is creating in the purpose of colection and updating data of the central counterparty clearing houses (CCP).

As there is no standards in reporting for CCP. Each CCP report in different way. Above that there is no guarantee that single CCP report is similar in structure for all quarters (most of them provide some changes from 'time to time'). 
Taking this into account this app create single funcion for single CCP. But as I mentioned before there is no guarantee for the future upating data as there is no guarantee for the way CCP is going to be reporting data.

All of the functions are collected in one function **ccp_colect()**, it allows you to colect and convert single file in the purpose of further concating 

For adding new quarter to existing dataset use **ccp_add()**

As some data are aggregated annualy and some quarterly use **ccp_aggr_and_save()** to aggregate them annualy

For concating files from one CCP use **ccp_concat()**

For concating all concated data use **ccp_concat_all()**

For sorting without aggregation (annual data) use **ccp_aio_sort()**

For sorting with aggregation (annual data) use **ccp_aio_aggr_sort()**
