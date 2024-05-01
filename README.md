# AI-Assisted Code Reviewer

This Streamlit app uses OpenAI's GPT-3 API to provide an AI-assisted code review. The app takes user-inputted code and offers suggestions for improvements or fixes. 

## Setup and Installation

1. Fork this repository.
2. Create a new file named `api_key.txt` in the `keys` directory. 
3. Obtain an API key from OpenAI and paste it into the `api_key.txt` file. You can sign up and obtain a key from [here](https://openai.com/api/).
4. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

5. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

## Usage

- Launch the app and you will see a text area where you can enter your code.
- Select the programming language of your code from the dropdown menu.
- Click the "Generate" button to get an AI-assisted review of your code.

## Supported Languages

- Python
- JavaScript
- Java
- C#

## Contributing

Pull requests are welcome! Please follow the standard fork-and-pull workflow:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.

Please ensure that your code follows the existing style and format, and that your changes do not break the existing functionality. 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
