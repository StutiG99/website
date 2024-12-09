---
author: Stuti Goyal
categories:
- Theme Features
- R
- package
draft: false
excerpt: This project aims to analyze and visualize sentiments in UK and US news media regarding various countries' COVID-19 responses over time by leveraging APIs. 
layout: single
tags:
- hugo-site
title: Sentiment Analysis of News Reporting During COVID-19
---
At the two-month mark of the COVID-19 pandemic (a relatively short period in hindsight) the virus had already dominated global news, with coverage focusing on economic impacts, government responses, and emerging conspiracies. Countries like Denmark and South Korea implemented swift measures, effectively reducing future costs and fatalities. Denmark's approach ensured job retention and paid leave during disruptions. In contrast, the United States exhibited a fragmented response, with varying state mandates and public protests against perceived freedom restrictions. To analyze media sentiments toward different countries' COVID-19 management, we aimed to:

1. Assess sentiments in UK and US news articles using the News API.
2. Track sentiment changes over recent months.
3. Visualize data through line graphs and word clouds.

We anticipated positive sentiments toward Taiwan, South Korea, and Denmark, and negative sentiments toward the UK, India, and the USA. For Italy, we expected negative yet sympathetic tones. Initially positive sentiments toward China were predicted to decline due to emerging controversies.

Our findings have been featured on a Medium blog post [here](https://medium.com/@cylama/sentiment-analysis-of-covid-19-related-news-media-across-nations-ab51fb0d72c9#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6IjM2MjgyNTg2MDExMTNlNjU3NmE0NTMzNzM2NWZlOGI4OTczZDE2NzEiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJhdWQiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJzdWIiOiIxMDA4NDE2ODk4MzA4ODQ4ODMyNzkiLCJlbWFpbCI6InN0dXRpZ295YWwxQGdtYWlsLmNvbSIsImVtYWlsX3ZlcmlmaWVkIjp0cnVlLCJuYmYiOjE3MzI3NTgyMjEsIm5hbWUiOiJTdHV0aSBHb3lhbCIsInBpY3R1cmUiOiJodHRwczovL2xoMy5nb29nbGV1c2VyY29udGVudC5jb20vYS9BQ2c4b2NLZWtTYTlKLW1CMkZRNkcwWmZKaElNa1dVNjhZS1Y3Uk10a2xPWEJEY0M4VWJuZXA3ZkNRPXM5Ni1jIiwiZ2l2ZW5fbmFtZSI6IlN0dXRpIiwiZmFtaWx5X25hbWUiOiJHb3lhbCIsImlhdCI6MTczMjc1ODUyMSwiZXhwIjoxNzMyNzYyMTIxLCJqdGkiOiJmYTBlYjMxZTExMGFhM2YxOTlkNWYwMTdiNzcyYjdkNGFiZDIxYmJiIn0.WEAkUsqJibEouWyFtXO8UtQJv0BG5ssAlbpnNw3t55B3GCC6q-DpIhaWSa4-Rzh_Em66hVeLDI_G-aMQKllE5_ylKdHkKlZBpMLLMpBPv-mWJO0WbJclwoBpKLhj-Xtzv1OHdPtjFq5pKqjIQyKpBiNWbwF4MZd5xImQhH5CLoqd3QzAY5z91h3uRyzWH624Rpp1uNpYkgCSvKN6wRUTwAQ-5T-jEVDoFKXuwznCSQE7aPf3l27YoSn_YQF_1BkaRxJoj1pmaCNXCgfz-17eUfRHR4mreI4cxd5Qb2eNFzK2F1UHdqKUi2T1ombOyecAxBdmMsMdjXbkqGh8UJHt2g). 


