# Email Automation using UiPath

## 📌 Project Overview  
This project automates email-based workflows using UiPath. It reads input from Excel, performs email processing tasks, and handles CSV creation/modification automatically.

## ✅ Key Features  
- Reads configuration and input data from an Excel file.  
- Automates sending and receiving emails based on rules.  
- Generates, updates and writes CSV files as output datasets.  
- Uses UiPath workflows (Main.xaml, mail_sequence.xaml, mainFlow.xaml) to structure the automation.

## 🛠️ Technology Stack  
- **RPA Platform**: UiPath  
- **Data Sources**: Excel (.xlsx) input, CSV output  
- **Workflows**: XAML files created in UiPath Studio  
- **Project Settings**: Defined in project.json  

## 📂 Project Structure  
Email_Automation_UiPath/
├── Main.xaml
├── mail_sequence.xaml
├── mainFlow.xaml
├── project.json
├── settings/
├── input/ExcelFile.xlsx
└── output/outputData.csv


## 🚀 Getting Started  
1. Clone the repository:  
   ```bash
   git clone https://github.com/VKM112/Email_-automation_using_uipath.git


Open the project in UiPath Studio.

Update the Excel input file with your data and configure your email settings (SMTP/IMAP) in the workflow.

Run the Main.xaml workflow.

Check the output/ folder for the generated CSV file(s).

📋 Usage Notes

Make sure you have UiPath Studio installed and licensed.

Ensure Excel and CSV file paths are correctly configured inside the workflows.

If using email automation, validate your email server/provider settings (SMTP, IMAP, credentials).

Verify that the Excel sheet headers match those expected by the workflow logic.

🎯 Future Enhancements

Add advanced email filtering and attachment handling.

Integrate a logging/dashboard to review automation runs and exceptions.

Support multi-sheet Excel input and dynamic mapping to CSV formats.

Deploy as a scheduled bot task in UiPath Orchestrator for fully automated runs.
