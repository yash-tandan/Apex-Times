# Apex-Times

Apex times is a salesforce news application that shows real time news data collected from news api. 
This project uses Lightning App page, Apex Class, LWC(Lightning Web Components) and other salesforce concepts for its use.

The steps followed for this project is:
  1. Remote Site Setting
  2. Creation of Lightning App Page
  3. Apex class to call REST API(news API)
  4. Display Data on Lightning Web Component
  5. Deploy your component

Remote setting was used to give access to the News api site as salesforce prevents calls to unauthorized network addresses.

Next step is to create a lightning app page where our news headlines will be displayed.

Then an apex class is created to call the News API(REST API). This apex class first checks if the server is responsive and
if responsive then stores the data gathered in a map so that the data can be divided easily according to our needs.

The next step is to create a LWC component from our VsCode. For that first connect to your org and then create a LWC component.
In this step we also design our page with the help of html,css and JavaScript. Html is used for providing structure to the page,
CSS to design the page while JavaScript to make the page interactive.

Last step is to deploy our app on app builder in our salesforce org.


## For Salesforce on VsCode

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
