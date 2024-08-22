# AI Storybook Generator

This project implements an AI Agent assistant using GPTScript, capable of chaining AI tasks together to create a complete Storybook with beautiful text and images, all generated from a single initial prompt. The project also showcases real-time processing, story storage, and more, leveraging the power of Next.js and OpenAI.

## Features

- **AI-Driven Storybook Creation**: Generate a fully fleshed-out Storybook with rich text and images from just a single prompt, entirely powered by the AI Agent.
- **Real-Time Process Visualization**: Watch the AI Agent in action as it builds the Storybook in real-time, with live updates streamed directly to the frontend.
- **Automated Story Storage**: All created stories are automatically stored on the server, managed seamlessly by the AI Agent.
- **Real-Time Streaming**: Implemented real-time streaming from the API endpoint to display the AI Agent’s processes as they happen.
- **Optimized User Experience**: Utilized caching in Next.js to create a fast and efficient user experience.
- **OpenAI Integration**: Integrated OpenAI's powerful APIs to generate content and images for the Storybook.
- **UI/UX Design**: Created a beautiful and intuitive frontend using Shadcn & Tailwind CSS.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ChiragShelar/storyteller.git
   cd ai-storybook-generator
    ```
2. Install dependencies:
    Make sure you have node installed, then run:
    ```bash
    npm install
    ```
3. Set up enviornment variables:
    Create a `.env` file in the root directory of the project to add your openAI API key.
    ```bash
    OPENAI_API_KEY=your-openai-api-key```
4. Start the development server:
    Run the following command to start the development server:
    ```bash
    npm run dev```
5. View the project:
    Open your browser and navigate to `http://localhost:3000`` to see the AI Storybook Generator in action.