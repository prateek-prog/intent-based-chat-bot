# intent-based-chatbot
 # Intent-Based Chatbot with Streamlit

An intent-based chatbot built using Streamlit, designed to understand user queries and provide relevant responses based on predefined intents.

## Features

- **Natural Language Processing (NLP):** Uses intent classification to understand user queries.
- **Streamlit UI:** Interactive and user-friendly web-based interface.
- **Customizable Intents:** Modify intents and responses as per project requirements.
- **Lightweight and Fast:** Runs efficiently on minimal resources.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/intent-chatbot-streamlit.git
   cd intent-chatbot-streamlit
   ```

2. **Create a Virtual Environment (Optional but Recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Streamlit App**
   ```bash
   streamlit run app.py
   intent-based-chat-bot-9.streamlit.app
   ```

2. **Interact with the chatbot**
   - Type your message in the input box.
   - The chatbot will provide responses based on predefined intents.

## Project Structure

```
intent-chatbot-streamlit/
│── data/
│   ├── greenskills.json          # Define chatbot intents and responses
│── models/
│   ├── intent_classifier.pkl # Trained intent classification model
│── app.py                    # Streamlit frontend
│── chatbot.py                 # Core chatbot logic
│── requirements.txt           # Required Python packages
│── README.md                  # Project documentation
```

## Customization

- Modify `data/greenskills.json` to add new intents and responses.
- Update `chatbot.py` to enhance chatbot logic.

## Dependencies

Ensure the following dependencies are installed:
```txt
streamlit
nltk
scikit-learn
spacy
```  
(Full dependencies listed in `requirements.txt`)

## License

This project is licensed under the MIT License - see the [LICENSE](3.89) file for details.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.


