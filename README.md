
# GPT-3 JabeBot Project for WhiteRabbit/HAS

## Project Overview
This project implements a chatbot using GPT-3, allowing users to interact with the bot via a Python-based interface. The project includes Python scripts to handle the chatbot logic and the required environment setup.

### Contents:
- **app.py**: Main application file that runs the chatbot.
- **jabebot.py**: Contains the core logic for the JabeBot functionality.
- **requirements.txt**: Lists the necessary Python packages for the project.

## How to Use
### Local Setup
1. **Clone the repository** to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. **Install the required dependencies** listed in the `requirements.txt` file. It is recommended to use a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows use 'env\Scripts\activate'
   pip install -r requirements.txt
   ```

3. **Set up your environment variables**. You will need an API key for OpenAI's GPT-3. Set it in your environment as follows:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key"
   ```

4. **Run the application**:
   ```bash
   python app.py
   ```

### Deployment
For deployment, you can use a platform like **Heroku**, which is ideal for Python apps with lightweight deployment needs.

#### Heroku Deployment
1. Log in to [Heroku](https://www.heroku.com/) and create a new app.
2. Add your OpenAI API key in the Heroku environment settings.
3. Push the repository to Heroku:
   ```bash
   git push heroku main
   ```
4. After deployment, Heroku will provide a URL where you can access the chatbot.

## Environment Variables
- `OPENAI_API_KEY`: Your GPT-3 API key from OpenAI. This key is required for the bot to function.

## License
This project is private and internal to `thedifferenceconsulting.com` for client use only. Unauthorized use is prohibited.

For further assistance, you can contact:
- Heather Renze (CTO, @heathriel on GitHub)
- Braulio Buccio (DevOps, @beebucio on GitHub)
