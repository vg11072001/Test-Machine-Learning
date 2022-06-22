# Test-Machine-Learning
The task was given by eyerlytics

## Approach, Tools and techniques
Steps performed: 
* Importing data in CSV format
* Did some data processing, as distribute X as 29 columns (having_IP_Address,	URL_Length,	Shortining_Service,	having_At_Symbol,	double_slash_redirecting,	Prefix_Suffix,	having_Sub_Domain,	SSLfinal_State,	Domain_registeration_length,	Favicon	port,	HTTPS_token,	Request_URL,	URL_of_Anchor,	Links_in_tags,	SFH	Submitting_to_email,	Abnormal_URL,	Redirect,	on_mouseover,	RightClick,	popUpWidnow,	Iframe,	age_of_domain,	DNSRecord,	web_traffic,	Page_Rank,	Google_Index,	Links_pointing_to_page,	Statistical_report) as Input and 1 columns (Result) as Output.
*  Splitted the data into X_train and X_test.
*  Then did feature scaling 


### For SVM 
* Trained the Kernel SVM model on the Training set
![image](https://user-images.githubusercontent.com/67424390/174987108-a02c1cdd-ed8a-4ca7-b01f-17e35336be70.png)

### FOR ANN
*  Build the ANN model.
![image](https://user-images.githubusercontent.com/67424390/174987021-e1dcf436-9b20-4084-ae51-4066625af5bd.png)


*  Predicted the result of a single observation

## Accuracy of the model with SVM Classifier!
![image](https://user-images.githubusercontent.com/67424390/174986782-077f370d-2a81-4c3f-b0fb-86ec6cbd4a0a.png)


## Accuracy of the model with ANN!
![image](https://user-images.githubusercontent.com/67424390/174840510-90ab33e8-c136-4ba7-862b-3d37d3002019.png)

