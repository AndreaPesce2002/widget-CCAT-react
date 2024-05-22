# Widget CCAT - Your Magical Assistant Cat

[![npm version](https://img.shields.io/npm/v/widget-ccat.svg)](https://www.npmjs.com/package/widget-ccat) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Easily integrate a customizable conversational artificial intelligence into your website or application with the [Widget CCAT](https://www.npmjs.com/package/widget-ccat?activeTab=readme). This lightweight and versatile React component offers an engaging user experience thanks to its intuitive chat interface and entertaining cat animations.

## Main Features

* **Customizable AI Chat:** Connect the widget to your cheshire-cat.
* **Intuitive Chat Interface:** Provide your users with a smooth and modern chat experience.
* **Engaging Animations:** The Stregatto animates and interacts with users, making the experience more enjoyable.
* **Easy Integration:** Add the widget to your React project with just a few simple steps.
* **Lightweight and Fast:** Designed to be efficient and not slow down your website.

## Installation

Make sure you have Node.js and npm installed. Then, run the following command in your terminal:

```bash
npm install widget-ccat
```

## Usage
```js
import WidgetCCAT from 'widget-ccat';

function App() {
  return (
    <div>
      <WidgetCCAT 
        baseUrl="http://localhost" 
        port="1865"
        initialPhrase="Ciao! Sono il tuo assistente virtuale. Come posso aiutarti?"
        sorryPhrase="Mi dispiace, al momento non sono disponibile. Riprova più tardi."
        chatUnderneathMessage="Ricorda che sono ancora in fase di apprendimento e potrei commettere errori."
        // ... altre opzioni di personalizzazione
      />
    </div>
  );
}
```

## Customization Options (Props)
| Customization Options (Props) | Prop | Type | Description | Default Value |
|-------------------------------|------|------|-------------|---------------|
| baseUrl                      |      | string | Base URL of the CCAT server or your AI model. | localhost |
| port                        |      | string | Port of the CCAT server or your AI model. | 1865 |
| initialPhrase               |      | string | Welcome message of the bot. | "Hello I'm the Stregatto, a curious and courteous artificial intelligence. How can I help you?" |
| sorryPhrase                 |      | string | Error message of the bot. | "ops... the cat had some problems" |
| chatUnderneathMessage       |      | string | Informative message under the chat. | "LLM can make errors, watch out for hallucinations" |

## Contributions

If you want to contribute to the project, you're welcome Open an issue to report bugs or suggest new features, or send a pull request with your changes.

## License
[Copyright (C) 2024 Andrea Pesce](LICENSE)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
