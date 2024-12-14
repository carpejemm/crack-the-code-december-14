# Chatbot AI

Chatbox AI is an interactive chatbot application designed to engage users in meaningful conversations. It features a sleek and responsive interface, utilizes a generative language API to create intelligent responses, and enhances user experience with modern design practices.

## Features

- **Interactive Chat Interface**: A dynamic chatbox that handles user inputs and displays responses in real-time.
- **Generative AI Integration**: Powered by the Gemini Pro model for generating conversational responses.
- **Modern UI Design**:
  - Responsive layout for mobile and desktop devices.
  - Intuitive toggler button for opening and closing the chatbot.
- **Error Handling**: Informative error messages displayed when API issues arise.
- **Customizable**: Easily update API keys and extend functionality.

## Technologies Used

- **HTML5**: Markup for the chatbot structure.
- **CSS3**: Styling and layout with responsive design for various devices.
- **JavaScript**: Logic to handle chat interactions and API integration.
- **Google Fonts**: Elegant typography for a modern look.
- **Material Symbols**: Iconography for an enhanced user experience.

## Getting Started

Follow these steps to get the application running on your local machine.

### Prerequisites

- A modern web browser (e.g., Chrome, Edge, Firefox).
- A valid API key for the Gemini Pro generative language model.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/carpejemm/crack-the-code-december-14.git
   cd crack-the-code-december-14

2. Open the `index.html` file in your preferred browser:
3. Ensure you have a valid API key for the generative AI. Replace the placeholder in `script.js`.
4. Save your changes and refresh the browser.

## API Configuration
The application uses the Gemini Pro generative language model API for generating responses. Ensure you have an API key and update the API_KEY variable in script.js.

API URL:
https://generativelanguage.googleapis.com/v1/models/gemini-pro:generateContent?key=YOUR_API_KEY

# Setting Up Your API Key

To enable Chatbox AI to generate intelligent responses, you need to set up your API key in the `script.js` file. Follow these steps:

### Step 1: Open the `script.js` File
Open the `script.js` file using a text editor of your choice.

### Step 2: Locate the API Key Placeholder
Find the following line of code in the file:

`const API_KEY = "your-api-key-here";`

### Step 3: Replace the Placeholder
Replace `"your-api-key-here"` with your actual API key. After updating, the code should look like this:

`const API_KEY = "your-actual-api-key";`

### Step 4: Save the File
Save the changes to the `script.js` file.

### Step 5: Refresh Your Browser
Reload your browser to apply the changes and activate the API key.

## Important Notes

Keep your API key private: Do not share your API key in public repositories or with unauthorized individuals.

Secure your API key: Consider using environment variables or other secure methods to store sensitive information in production environments.

## Contact
For issues or suggestions, please create an issue in the GitHub repository or contact the developer at jerelydclaguda@gmail.com.