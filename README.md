# STPP-Public-Transportation-Planning-tool

<img src="images/vltreadme.jpeg" width="1000" />

STPP is an Online Program designed to meet a specific need to respond to requests and complaints from citizens/communities about public transport planning in Recife, Brazil.

Browse through the homepage, register, log in and begin proposing solutions. 

Click on the **Quick Guide** link at the top left of the screen and view the steps to complete an action request submitted by a public transport user.
<img src="images/quickguide2.jpeg"  />

## Inside User Interface Area - Logged In
<img src="images/userarea.png" />

1 - Receive the request by email from an ombudsman center in your inbox,

2 - Find out if requests or complaints are valid. Use maps, database search and legal consultation to explain the operation of the line mentioned in the request.


3 - if the requested itinerary does not exist, explain the reasons or propose a solution.

4 -  If necessary, discuss the situation with the planning team, find representatives of the bus operators, develop a solution and respond to the request.

### Sending a Complaint or request

From the side menu, press **SEND COMPLAINT** to open request/complaint form.
<img src="images/sendcomplaint.png"  />

Some sample complaints and requests are available for testing.

For this trial version it will be possible to send complaints and requests to your own inbox. 

Ombudsman messages are available in official version for transport sector analysts.

### Openning a Complaint or request

<img src="images/inbox.png"  />
Select INBOX on the side menu and access requests and complaints


Choose a request by pressing the REPLY button. Read the request carefully.
<img src="images/reply.png" width="800" />


### Investigating Complaints and requests

From the side menu, press the Search Database link to search for similar requests. Search by keyword, bus line code or nomenclature, subway station name or any other keyword that finds a similar situation.

<img src="images/searchdatabase.png" width="800" />

Choose Maps and Directions from the side menu and search for bus itineraries on google maps, specifying origin and destination, search for addresses, neighborhoods, bus terminals or subway stations to understand the operation of the line reported in the claim.

<img src="images/searchmap.png" width="800" />

On the side menu, press Legislation to open files in pdf format with the current laws that govern the public transport system in the metropolitan region of Recife. You will find the operation manual of the bus lines, the regulation of the integration system and the municipal laws of the cities that are part of the Metropolitan Transport Consortium.

Other options such as Discussion Forums and Chatroom with analysts, bus companies and the general population are needed to reach agreement on changes to the transport system more quickly.

### Finishing a Request/Complaint 

After investigating the facts and reaching a conclusion, click on the inbox link in the side menu and select the complaint by pressing the reply button. In future versions, the analyst will be able to dictate a response using a speech to text speech recognition tool.

<img src="images/confirmreply.png" width="800" />

A confirmation will be requested, giving the analyst the opportunity to review the question and confirm the sending of the answer with the solution found, or directing the citizen to make further referrals to the request.

## Settings

The beta version only allows the user to change their own password. Other options such as telephone number, email and additional information about the position and institution linked to public transport are restricted to public officials in the transport sector in the region. Map and database option settings will be implemented in future releases.

<img src="images/settings.png" />

### Changing Password

The only requirement is that the password be exactly 6 digits long and the username be at least 6 digits long.
The logged in user can change their password by confirming the username and entering a new six-digit password. The system confirms that the user is logged in and changes the password without the need to confirm email. In the official version, the government employee will enter the email and personal data registered at the time of hiring.

### Contact and Reporting a Bug

We need to evaluate the application performance. Feel free to submit a bug. We appreciate the effort.
The contact form uses gmail to send messages to the program developer. No name or email required to get in touch. Just send the subject and message.

<img src="images/contact.png" width="1000" />

## Limitations

When searching for maps, the Google Maps API needs to be implemented to increase search options.

Google Maps does not include integration of buses and subways results. It only shows the options for bus lines.

The database search needs to include the itineraries of all lines available in the system. For this, it is necessary to integrate the STPP with the State of Pernmabuco's cloud servers.

The application works with sensitive data sent by the ombudsman's servers. For this reason, these data will not be available for investigation. On the other hand, all legislation can be consulted during beta tests.

The users inbox loads some sample requests. The analyst can send new requests to the inbox by selecting Send Complaint/Request from the side menu. In the next version the analyst will receive the new messages through Gmail API.





