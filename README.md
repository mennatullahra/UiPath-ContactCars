# UiPath-ContactCars

## Overview
This project aims to automate the process of handling trigger emails received from clients. The main objective is to process each trigger email separately, extract search criteria from an Excel attachment, use the criteria to perform a search on the ContactCars website, consolidate the search results into an Excel report, and reply to the client with the generated report. 

## Dispatcher Process Steps

1. **Receive Trigger Email:**
    - The automation process begins when a trigger email is received.

2. **Separate Transactions:**
    - Each trigger email is treated as a separate transaction. This ensures that the automation process is isolated for each client request.

## Performer Process Steps

1. **Extract Search Criteria:**
    - Extract the desired features or search criteria from the Excel attachment received in the trigger email.

2. **Login to ContactCars Website:**
    - Use the extracted search criteria to log in to the ContactCars website.

3. **Perform Search:**
    - Input the search criteria into the website's search functionality to obtain relevant results.

4. **Consolidate Search Results:**
    - Consolidate the search results into an Excel sheet report.

5. **Reply with Excel Report:**
    - Reply to the trigger email with the generated Excel report as an attachment.

## Technology and Framework
- This project utilizes the UiPath RE Framework template, following best practices in Robotic Process Automation (RPA).

## Transaction Handling
- Each trigger email is treated as a transaction item, ensuring a clear and independent process for each client request.

## Excel Attachment Attribute
- The Excel attachment attribute is stored as a JSON string for efficient processing.

## Conclusion
This automation project streamlines the handling of trigger emails, ensuring accuracy and efficiency in responding to client requests. By adhering to best practices and utilizing the UiPath RE Framework, we aim to deliver a robust and reliable solution.

For any questions or issues related to this project, please refer to the project documentation or contact me.

## Supervision
This project has been done under the supervision of **ADVANSYS-ESC**, providing guidance and support throughout the development process.
