This repo contains the `raw` data used in https://github.com/JakeCracknell/drivingteststats

It also contains some messy Python Jupyter notebooks I wrote to aggregate the raw data and generate the JSON files used by the website. See `misc`, specifically `dvsa_data_analysis_6_generate_jsons.ipynb`.



# FOI Request 2024-08-16
https://www.whatdotheyknow.com/request/driving_test_fault_statistics_by


# FOI Response 2024-10-09
Public Liaison Team              
Driver and Vehicle Standards Agency
1 Unity Square
Queensbridge Road
Nottingham NG2 1AY

 
Our ref: 2409-056666
  
Dear Jake Cracknell
 
Information requested under the Freedom of Information Act (FoIA) 
 
Further to your emails of 5 September, I can confirm that we hold the information you have requested and have handled your request within the terms of the FoIA.  
 
Your request and our response is as follows:  

I believe I have taken appropriate steps to ensure that personal data is anonymised to the extent necessary. However, I am happy to work with you to refine the request further if you could provide specific details on the elements you have deemed personal data. For example, I suggested using a randomly generated UUID for the Test ID to ensure that no individual can be identified, and I would appreciate your confirmation on whether this approach would sufficiently anonymise the data.

The purpose of the request is to obtain insights on which faults are most common for each test centre, and which ultimately lead to test fails. If timestamps are stored, knowing how far into the test will yield additional insights. Any useful insights I gain can be shared to help candidates prepare to take tests in areas they are unfamiliar with.

For example, on average, a 'Junctions - observation' serious fault occurs on 5% of tests, but for test centre XYZ, it occurs 8% of the time and 20% of those are in the first 5 minutes. Conclusion: candidates should be extra careful about navigating access roads to the XYZ test centre. Knowing test failure rates by time of day and the underlying fault might yield insights like "test centre XYZ sees the most dangerous faults during rush hour, or after sunset". Ultimately, I would like to create a tool that will tell candidates, should they book a test at a certain time and test centre, what areas of driving should they practice the most to achieve success.

I hope this provides the clarity needed to process the request while maintaining compliance with data protection rules. If you still believe adjustments are required, I would appreciate your specific guidance on what parts of the request remain problematic.

Please could you provide the following data concerning Category B car driving tests, in a machine-readable format. This will help candidates know what to focus their practice sessions on, depending on their chosen DTC and time.

We have had ongoing discussions with the relevant department who hold this data regarding your request. Due to the amount of data that is recorded on the excel documents, this was going to take over 24 hours to make all the document’s user friendly, which we are unable to do as this would exceed the cost of compliance. To meet your expectations we can only supply you with the raw data.

We can only provide these documents in excel format, however, as already mentioned due to the volume of data excel will only show you 9 months of data, we can however confirm there is 12 months of data on these documents (which is dated below). Therefore, if you have problems loading the files, it might be worth trying another platform to view these documents. 

Please see attached Annex A which will contain driving test centres addresses, post code’s, latitude and longitude and test centres identification (ID)

Please see Annex B attached, which will have category B driving test and dating between 01/04/2023 – 30/03/2024, driving test centre name, slot time (what time the test started), how many attempts and results are passed or failed
 
Please see attached Annex C which is in a zip format, due to the size of the file. will include category B driving test and dating between                                                          01/04/2023 – 30/03/2024, ID, fault categories. 

Please see attached Annex D, which will have category B driving test and dating between 01/04/2023 – 30/03/2024, driving test centres, manoeuvres, total faults, serious, dangerous and driver’s faults, test centre ID.

If you are unhappy with the way we have handled your request, you can ask for an internal review to be conducted by our Information Management and Security Team by emailing: FOI@dvsa.gov.uk. This must be done within 40 days of this email.   
 
If you are not happy with the outcome of your internal review, you have the right to contact the Information Commissioner’s Office (ICO) for a decision. You can find further information about the ICO's complaints process on its website.

Yours sincerely


# Annex A Updated 2024-10-24

I requested Annex A was regenerated as the original extract had truncated the coordinates to an unusable level of precision. Annoyingly they dropped TC_ID in the next extract, but I joined them successfully using the DTC name.





