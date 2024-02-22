<div align="center">
<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

<h1 align="center">Empress: Export Settings - Streamline Your Data Exports</h1>
<p align="center">
An essential tool that allows users to predefine export fields, simplifying data export operations and enhancing user experience.
<br />
<a href="https://grow.empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/export_settings/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/export_settings/issues">Request Feature</a>
</p>
</div>

## About The Project

### 📖 Overview
Empress: Export Settings is a robust, user-friendly tool tailored for those who frequently export data. It allows users to predefine the fields they wish to export, saving precious time and reducing manual effort. This feature is available for any doctype in Empress.

### 🌟 Key Features
- Define prechecked fields for any doctype
- Simplify the data export process
- Enhance user experience by minimizing manual selections

## Getting Started

### Prerequisites
Ensure you have Empress installed before proceeding.

### Installation
Follow these straightforward steps to set up a development environment:

```sh
# Navigate to your Empress bench folder
cd path/to/your/bench 

# Clone the GitHub repository
git clone https://github.com/empress-eco/export_settings.git

# Install the app onto your site
bench --site your-site-name install-app export_settings

# Migrate the database
bench migrate

# Restart your Empress server
bench restart
```

## Usage
Using Empress: Export Settings is a breeze. Here's a quick start guide:

_To create a new Export Setting:_
1. Go to the 'Export Settings' doctype.
2. Select the doctype you want to configure.
3. Check the fields that should be prechecked during export.
4. Save the document.

_To export data:_
1. Navigate to the doctype for which you've set the export settings.
2. Click on the 'Export' button.
3. Notice that the fields specified in the 'Export Settings' are prechecked.

## Contributing
We welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License
This project is licensed under the MIT License. Your contributions will also be licensed under the same.

### Acknowledgements
A special note of gratitude to the Empress Community for their foundational contributions to this project. Their innovation and dedication have been instrumental in building the essential tools that power this project. We are profoundly thankful for their pioneering work and persistent support.