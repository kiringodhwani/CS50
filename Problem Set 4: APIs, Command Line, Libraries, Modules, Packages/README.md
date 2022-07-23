**Assignments from Week 4 of CS50's Introduction to Programming with Python at Harvard**

Week 4 was spent learning about **Libraries, Command Line Arguments, APIs, and Modules**. Below are descriptions of each of the programs in this folder:  
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------
  
1. **professor.py**: 
   - Prompts the user for a level (either 1, 2, or 3). If the user does not input 1, 2, or 3, the program prompts again.
   - Randomly generates ten (10) math problems formatted as X + Y = , wherein each of X and Y is a non-negative integer with  digits.
   - Prompts the user to solve each of these problems. If an answer is not correct (or not even a number), the program outputs EEE and prompts the user again, allowing the user up to three tries in total. If the user has still not answered correctly after three tries, the program outputs the correct answer.
   - Ultimately outputs the user’s score, a number out of 10.
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------
  
2. **bitcoin.py**: 
   - Expects the user to specify as a command-line argument the number of Bitcoins, 'n', that they would like to buy.
   - Queries the API for the CoinDesk Bitcoin Price Index at https://api.coindesk.com/v1/bpi/currentprice.json, which returns a JSON object, among whose nested keys is the current price of Bitcoin as a float.
   - Outputs the current cost of 'n' Bitcoins in USD to four decimal places, using commas as thousands separator.
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------
  
3. **figlet.py**: Uses FIGlet to allow users to print out messages of their choice in FIGlet fonts:
   - Expects zero or two command-line arguments:
      - Zero if the user would like to output text in a random font.
      - Two if the user would like to output text in a specific font, in which case the first of the two should be -f or --font, and the second of the two should be the name of the FIGlet font.
   - Prompts the user for a str of text.
   - Outputs that text in the desired FIGlet font.
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------


6. **emojize.py**: Prompts the user for a str in English and then outputs the “emojized” version of that str, converting any codes (or aliases) therein to their corresponding emoji. Uses the built-in emoji module.  
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------