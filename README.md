# LinkedIn Reply Extension

## Description

The LinkedIn Reply Extension is an AI-powered tool designed to help users generate quick and relevant replies to LinkedIn messages. By analyzing incoming messages, the extension provides contextually appropriate suggestions, saving users time and enhancing their communication efficiency.

## Video Demo

[![Watch the video](https://img.youtube.com/vi/CvUCMlF3rz8/maxresdefault.jpg)](https://www.youtube.com/watch?v=CvUCMlF3rz8)

*Click the image above to watch a demonstration of the AI-powered LinkedIn Reply Extension in action.*

*The demo showcases the following tasks:*

1. Open a LinkedIn message conversation.
2. Click the edit icon that appears in the message box.
3. Enter your prompt in the modal.
4. Click "Generate" to receive AI-suggested replies.
5. Use "Regenerate" for alternative suggestions.
6. Click "Insert" to add the selected message to your LinkedIn conversation.

## Features

- **AI-Powered Replies**: Quickly generates contextual message suggestions for LinkedIn conversations.
- **Customizable Templates**: Allows tailoring responses to specific job titles or message types.
- **Time-Saving**: Provides fast, intelligent replies with minimal effort.

## Tech Stack

- **WXT**: Web Extension Framework for streamlined extension development.
- **React**: Used for building responsive user interface components.
- **TypeScript**: Ensures type-safe JavaScript development.
- **Tailwind CSS**: For styling the extension UI.

## Installation

Follow these steps to get the project up and running on your local machine:

1. Clone this repository:
    ```bash
    git clone https://github.com/Sandesh-Upadhyay/Linkedin-reply.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Linkedin-reply
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Run the project:
    ```bash
    npm run dev  # for development mode
    npm run build  # for production build
    ```

## Usage

1. Open a LinkedIn message conversation.
2. Click the edit icon that appears in the message box.
3. Enter your prompt in the modal.
4. Click "Generate" to receive AI-suggested replies.
5. Use "Regenerate" for alternative suggestions.
6. Click "Insert" to add the selected message to your LinkedIn conversation.

## Development

- **`content.ts`**: The main content script injecting functionality into LinkedIn pages. A mix of Tailwind CSS and inline CSS is used due to compatibility issues and cross-origin policy.
- **React components**: Responsible for the UI, including the modal and message generation interface.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or issues, please contact **Sandesh Upadhyay**.
