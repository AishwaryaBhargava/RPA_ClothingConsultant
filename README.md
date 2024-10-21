# RPA Clothing Consultant

An automated clothing consultation process built using UiPath RPA (Robotic Process Automation).

## Project Overview

The Clothing Consultant is an automated process designed to assist with clothing-related tasks. This project leverages UiPath's automation capabilities to streamline clothing consultation workflows.

## Technical Details

### Project Specifications
- **Project Name**: ClothingConsultant
- **Project ID**: ecb7ced0-cbbb-4e65-9dc9-d340703048c1
- **Studio Version**: 19.12.0.61
- **Project Version**: 1.0.0
- **Framework**: Legacy
- **Expression Language**: VisualBasic

### Dependencies
- UiPath.Excel.Activities (2.8.0-preview)
- UiPath.Mail.Activities (1.8.0-preview)
- UiPath.System.Activities (19.12.0-preview)
- UiPath.UIAutomation.Activities (19.12.0-preview)

### Runtime Configuration
- **Execution Type**: Workflow
- **Attended/Unattended**: Unattended
- **User Interaction Required**: Yes
- **Pausable**: Yes
- **Auto Dispose**: No
- **Supports Persistence**: No

## Setup Instructions

1. Clone this repository:
```bash
git clone https://github.com/AishwaryaBhargava/RPA_ClothingConsultant.git
```

2. Open UiPath Studio (version 19.12.0.61 recommended)
3. Open the project by selecting the `project.json` file
4. Install required dependencies if prompted
5. The main workflow is located in `Main.xaml`

## Features

- Automated clothing consultation workflow
- Excel integration for data processing
- Email automation capabilities
- System and UI automation features

## Project Structure

- `Main.xaml`: Primary workflow file
- `project.json`: Project configuration and dependencies
- Additional workflow files (if any)

## Prerequisites

- UiPath Studio (v19.12.0.61 or compatible)
- .NET Framework (Legacy)
- Microsoft Excel (for Excel activities)
- Email client (for mail activities)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
