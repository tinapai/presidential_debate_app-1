# Presidential Debate Simulator

The Presidential Debate Simulator is an interactive web application designed to simulate a debate between two presidential candidates. Users can ask questions, read the candidates' responses, vote on the best answers, and test their knowledge with trivia questions about US Presidents.

## Features

- **Interactive Debate**: Ask questions and receive responses from Candidate A and Candidate B.
- **Voting System**: Vote for the best response and see the overall results.
- **Trivia Section**: Test your knowledge with trivia questions about US Presidents.
- **Earn Badges**: Earn badges for participation and correct answers in the trivia section.

## How to Use

1. **Ask a Question**: Enter your question in the input box and click "Ask".
2. **Read Responses**: Review the responses from Candidate A and Candidate B.
3. **Vote**: Vote for the response you like best by clicking the "Vote" button under the candidate's response.
4. **End Debate**: Click "End Debate" to see the results.
5. **Test Your Knowledge**: Answer trivia questions by selecting the correct candidate.

## Decrypting the API Key

To decrypt the API key on Windows, follow these steps:

1. Ensure you have OpenSSL installed on your system. If not, download and install it from [OpenSSL for Windows](https://slproweb.com/products/Win32OpenSSL.html).

2. Download the `api_key.enc` file from this repository.

3. Open a terminal (Command Prompt, PowerShell, etc.) and navigate to the directory containing `api_key.enc`.

4. Run the following command to decrypt the API key:
   ```sh
   openssl enc -aes-256-cbc -d -in api_key.enc -out api_key.txt -pass pass:judge123!! -pbkdf2

For Unix (Linux/Mac):
1. Ensure you have OpenSSL installed on your system. You can install it using your package manager if it's not already installed.

For Linux:

sudo apt-get install openssl  # Debian/Ubuntu
sudo yum install openssl      # CentOS/RHEL
sudo pacman -S openssl        # Arch Linux

For Mac:

brew install openssl

2. Download the api_key.enc file from this repository.

3. Move the api_key.enc file to your desired directory (e.g., your home directory).

4. Open a terminal and navigate to the directory containing api_key.enc. For example:

cd ~/Desktop

5. Run the following command to decrypt the API key:

openssl enc -aes-256-cbc -d -in api_key.enc -out api_key.txt -pass pass:judge123!! -pbkdf2

6. This will create a file named api_key.txt in the same directory containing the decrypted API key.


## Getting Started

To run this project locally:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/presidential-debate-simulator.git
2. Navigate to directory:
   cd presidential-debate-simulator
3. Open script.js and paste the decrypted apiKey into line 39 and 321 and click save
   
4. Open index.html in your web browser. (Best using Chrome)

## License

This project is licensed under the Testing Purposes License - see the [LICENSE] file for details.

