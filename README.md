# Google Drive vs Dropbox

Comparing Google Drive and Dropbox from a developer point of view.

|                   | Google Drive | Dropbox                |
| ----------------- | ------------ | ---------------------- |
| Cost per Month    | $ 9.99       | $ 9.99 + VAT           |
| Storage           | 1 TB         | 1 TB                   |
| Cost / GB / Month | $ 0.00999    | $ 0.00999              |
| API               | &#10003;     | &#10003;               |
| Authentication    | OAuth 2.0    | OAuth 2.0 / API Key    |

## Cost per Month

### Google Drive

The cost of 1 TB storage varies from country to country.

| Cost     | Country                  | USD (2017-09-13) |
| -------- | ------------------------ | ---------------- |
| 9.99 USD | United States of America  | N/A              |
| 7.99 GBP | United Kingdom           | 10.63 USD        |
| 159 ZAR  | Republic of South Africa | 12.22 USD        |
| 650 INR  | Republic of India        | 10.15 USD        |


### Dropbox

Keep in mind that VAT will be added to your monthly bill where applicable. Costs may differ in certain countries as seen below with United Kingdom.

| Cost     | VAT      | Country                  | Total     |
| -------- | -------- | ------------------------ | --------- |
| 9.99 USD | 0 USD    | United States of America  | 9.99 USD  |
| 7.99 GBP | 0 USD    | United Kingdom           | 7.99 GBP  |
| 9.99 USD | 1.40 USD | Republic of South Africa | 11.39 USD |
| 9.99 USD | 0 USD    | Republic of India        | 9.99 USD  |


## Storage

Although both, Google Drive and Dropbox, have a free option, we went with the 1 TB option as less than 10 GB would only be suitable for a handful of scenarios and the 1 TB should also be suffient for quite some time. When you reach this limit you should consider moving to Cloud Storage by Amazon.

## API

| Feature             | Google Drive | Dropbox  |
| --------------------| ------------ | -------- |
| Upload Files        | &#10003;     | &#10003; |
| - Simple Uploads    | &#10003;     | &#10003; |
| - Multipart Uploads | &#10003;     | &#10005; |
| - Resumable Uploads | &#10003;     | &#10003; |
| Download Files      | &#10003;     | &#10003; |
| - Temporary Link    | &#10005;     | &#10003; |
| Meta Data           | &#10005;     | &#10003; |
| - File Hash         | &#10005;     | &#10003; |

## Authentication

Google Drive only allows OAuth 2.0 authentication which does not allow one to use their API without a web interface. Dropbox has the option to use OAuth 2.0 as well as the option use an API key. The API key allows a developer to build applications and services on top of Dropbox.

## Conclusion

Coming Soon...