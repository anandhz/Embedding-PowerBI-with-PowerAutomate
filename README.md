# Embedding-PowerBI-with-PowerAutomate

## Project Description

In this project, I have integrated Microsoft Power Automate with Power BI to enhance the interactivity and functionality of Power BI reports. This integration allows users to trigger a Microsoft Flow directly from within a Power BI report. By clicking a button within the report, users can export data from a specific visual and receive it via email in the form of a visually appealing HTML table. This project demonstrates how to streamline data export processes and improve user experience by automating data delivery in an easy-to-read format.

## Features

- **Power Automate Integration**: Seamlessly trigger automated workflows from within Power BI reports.
- **Data Export**: Export data from a specific visual within the report with a single click.
- **Email Delivery**: Automatically send the exported data to the current report viewer's email address.
- **HTML Table Formatting**: Use HTML table functions in Power Automate to create and style visually appealing tables.
- **Dynamic Content**: Ensure the data is dynamically generated based on the specific visual and the current viewer's context.

## Flow Structure

![Flow Structure](image_src/Capture.png)
![Flow Structure](image_src/Capture1.png)
*This image illustrates the overall structure of the Power Automate flow used in this project.*

## HTML Table Design & Styling

![HTML Table Design & Styling](image_src/Capture4.png)
![HTML Table Styling](image_src/Capture5.png)
*This image shows the design and styling of the HTML table within the Power Automate flow.*

## Output Table Example

![Output Table](image_src/Capture6.png)
*This image provides an example of the output table that is sent via email to the report viewer.*

## How It Works

1. **User Interaction**: The user views a Power BI report and clicks a button embedded in the report.
2. **Trigger Flow**: The button click triggers a pre-configured Power Automate flow.
3. **Data Export**: The flow exports the data from the specific visual that the user interacted with.
4. **HTML Table Creation**: The flow formats the exported data into a well-styled HTML table.
5. **Email Notification**: The HTML table is sent to the user's email address as part of the email body, ensuring the data is both accessible and aesthetically pleasing.

## Setup Instructions

1. **Prerequisites**:
    - A Power BI report with the necessary visuals.
    - Microsoft Power Automate subscription.
    - Appropriate permissions to create and manage flows.

2. **Create the Flow**:
    - Open Power Automate and create a new flow.
    - Configure the flow trigger to be a Power BI button click.
    - Add actions to export data from the Power BI visual.
    - Use the HTML table function to format the exported data.
    - Configure the flow to send an email to the current viewer with the HTML table included.

3. **Embed the Button in Power BI**:
    - Go to Power BI Desktop and open your report.
    - Add a button visual and configure it to trigger the Power Automate flow.

4. **Test the Integration**:
    - Publish the report to the Power BI service.
    - Test the button to ensure the flow is triggered and the email is received with the correctly formatted data.

## Conclusion

This integration between Power Automate and Power BI demonstrates how powerful automation can enhance data interaction and delivery within reports. By following the setup instructions, you can replicate this functionality in your own Power BI reports, providing users with a seamless and efficient way to export and receive data.

For more details, please refer to the attached images that provide a visual guide to the flow structure, HTML table design, and example output.
