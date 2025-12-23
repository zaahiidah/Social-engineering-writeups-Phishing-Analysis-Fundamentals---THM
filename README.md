# Social Engineering Write-Up
Name: ZAHIDAH AZ-ZAHRA BINTI SAFARIZAM
ID: 52215226218
Platform: TryHackMe

Exercise: Phishing Analysis Fundamentals<br>
1.	Objective<br>
To identify the components involved in sending an email and to understand how to analyze email headers.<br>

2.	Tools/Platform Used<br>
    •	TryHackMe<br>
    •	CyberChef<br>
    •	Base64.Guru<br>

3.	Steps Taken<br>
      1. Identified the email headers and email body.<br>
      2. Analyzed key email header fields such as From, Subject, Date, and To.<br>
      3. Viewed the raw email content to examine detailed header information.<br>
      4. Identified suspicious elements within the email details.<br>
      5. Analyzed the email body for attachments and content types.<br>
      6. Interacted with attachments by decoding files and defanging URLs.<br>

4.	Findings/What I learned<br>
    •	Learned how to view the raw source of an email, including the header and body.<br>
    •	Understood the importance of analyzing email content for attachments, encoded data, and other suspicious elements.<br>
    •	Gained a better understanding of the relationship between the email sender and recipient information.<br>

5.	Conclusion<br>
This exercise strengthened my understanding of email structure and phishing analysis techniques. It showed how attackers can also manipulate email elements and emphasized the need to analyse email headers, email content and email attachments attentively to identify phishing attacks.<br>


6.	Evidence<br>

<img width="452" height="394" alt="image" src="https://github.com/user-attachments/assets/6a957126-bd76-4d04-b27b-07251b94ad82" />
 
Figure 1: Types of email<br><br>

<img width="870" height="265" alt="image" src="https://github.com/user-attachments/assets/7ad3f625-9a77-4f59-89f5-7a378acb3e42" />
 
Figure 2: email1.eml<br><br>

<img width="614" height="536" alt="image" src="https://github.com/user-attachments/assets/955e6864-554d-4cfc-8e87-8b29d78dfb96" />
 
Figure 3: email1.eml raw details<br><br>

<img width="567" height="540" alt="image" src="https://github.com/user-attachments/assets/06f4e7e8-deb0-457c-b325-c05d3bd9002b" />
 
Figure 4: email2.eml <br><br>

<img width="873" height="447" alt="image" src="https://github.com/user-attachments/assets/cfa0ec55-a391-48b8-8270-f27859de975d" />
 
Figure 5: Decode email2.eml .pdf content-type<br><br>

<img width="703" height="393" alt="image" src="https://github.com/user-attachments/assets/04682488-75c3-4d84-92e2-acb632579d50" />
 
Figure 6: email3.eml<br><br>

<img width="673" height="619" alt="image" src="https://github.com/user-attachments/assets/a70d9ab6-1d43-42dc-9b0c-0cc249b5fac6" />
 
Figure 7: email3.eml raw details<br><br>

<img width="702" height="474" alt="image" src="https://github.com/user-attachments/assets/a0d83e4a-da25-4719-86ed-fc98113dde27" />
 
Figure 8: Defang URL for email3.eml<br><br>

<img width="709" height="371" alt="image" src="https://github.com/user-attachments/assets/3f18c950-ff8f-42cc-a729-ad3ec1982bef" />
 
Figure 9: Complete Task<br><br>

