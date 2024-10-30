# Casper - The Fresh Connection Sales Assistant

**Casper** is a dedicated, modest AI assistant designed to help students and professionals excel in the **Sales Manager** role within the business simulation game *The Fresh Connection*, developed by Inchainge. While Casper may be humble, he brings valuable insights into sales strategy, negotiation, and customer relationship management, providing tailored guidance for in-game success.

## Overview

Casper focuses on helping users optimize their sales performance by providing practical, action-oriented advice. Whether you're working on boosting customer engagement, refining sales strategies, or negotiating deals, Casper has you covered with targeted recommendations based on *The Fresh Connection's* unique demands.

**Key Capabilities:**
- **Lead Generation**: Advice on finding and targeting the right customer segments.
- **Deal Negotiation**: Tips on structuring and negotiating sales deals to align with company goals.
- **Customer Relationship Management**: Strategies for building long-term customer relationships to maximize sales performance.
- **Sales Planning**: Guidance on creating effective sales plans that align with market demands and company capacity.

## Integration Guide

To add Casper to your *The Fresh Connection* simulation setup, you need to integrate the provided chatbot script into your platform, allowing users to interact with Casper directly.

### Steps to Integrate Casper:
1. Copy the script snippet below into the `<head>` section of your HTML file.

    ```html
    <!-- Casper Chatbot Script -->
    <script>
      window.difyChatbotConfig = {
        token: 'qAPFrmdwiQzbV5NG',
        baseUrl: 'https://web-production-ae39.up.railway.app'
      }
    </script>
    <script
      src="https://web-production-ae39.up.railway.app/embed.min.js"
      id="qAPFrmdwiQzbV5NG"
      defer>
    </script>
    ```

2. Style Casper’s chatbot appearance to match your app's look. You can update the bubble color or window size with CSS:

    ```css
    #dify-chatbot-bubble-button {
      background-color: #1C64F2 !important;
    }
    #dify-chatbot-bubble-window {
      width: 24rem !important;
      height: 40rem !important;
    }
    ```

### Accessing Casper’s Assistance

Users can click on Casper’s chat bubble to start a conversation and receive actionable, step-by-step sales advice directly relevant to *The Fresh Connection* simulation.

## Response Style

Casper is trained to respond in a clear, structured, and goal-oriented manner:
- **Direct**: Quick, straightforward instructions focused on improving sales performance.
- **Actionable**: Each response is designed to encourage immediate, measurable actions.
- **Concise**: Avoids lengthy explanations and focuses on what matters to win in *The Fresh Connection*.

## Example Interactions

To get started, here are a few example questions you can ask Casper:
- "Casper, how can I improve our lead generation strategy?"
- "What are the best ways to negotiate better sales terms in this game?"
- "How should I prioritize customer accounts to increase sales efficiency?"

With Casper, students and professionals in *The Fresh Connection* gain a valuable, hands-on sales mentor, ready to help them elevate their performance with real-time, tailored advice.

---

Casper is here to support your journey toward mastering sales management in *The Fresh Connection*, all while keeping things practical and straightforward. Enjoy optimizing your strategies and enhancing your gameplay with Casper’s guidance!
