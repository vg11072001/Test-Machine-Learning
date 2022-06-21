# Test-Machine-Learning
The task was given by eyerlytics

## Approach, Tools and techniques
Steps performed: 
* Importing data in CSV format
* Did some data processing, as distribute X as 29 columns (having_IP_Address,	URL_Length,	Shortining_Service,	having_At_Symbol,	double_slash_redirecting,	Prefix_Suffix,	having_Sub_Domain,	SSLfinal_State,	Domain_registeration_length,	Favicon	port,	HTTPS_token,	Request_URL,	URL_of_Anchor,	Links_in_tags,	SFH	Submitting_to_email,	Abnormal_URL,	Redirect,	on_mouseover,	RightClick,	popUpWidnow,	Iframe,	age_of_domain,	DNSRecord,	web_traffic,	Page_Rank,	Google_Index,	Links_pointing_to_page,	Statistical_report) as Input and 1 columns (Result) as Output.
*  Splitted the data into X_train and X_test.
*  Then did feature scaling 
*  Build the ANN model (I choosed ANN technique to bulid my beacuse in dataset the input variable are 29, which is large number for input, while at the same time mutivarible regression can be performed but it will not provide much clearity in visualization.
*  Predicted the result of a single observation

Visualizations

## Accuracy of the model
![image](https://user-images.githubusercontent.com/67424390/174840510-90ab33e8-c136-4ba7-862b-3d37d3002019.png)

