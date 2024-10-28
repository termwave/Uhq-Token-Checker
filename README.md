# 🚀 Ultimate Discord Token Checker 🚀

**Unlock the potential of your Discord tokens with our powerful checker script!** Whether you're a developer, server manager, or just curious about your tokens, this script provides comprehensive insights into their status and boosts.


## 🌟 **Features:**

- 🔍 **Token Verification:** Check the status of your Discord tokens to see if they are locked, invalid, or have Nitro.
- 🎁 **Boost Status:** Determine if your tokens have 1 or 2 boosts left.
- 📝 **Detailed Output:** Results are neatly categorized into different files based on token status.
- ⚡ **Multi-Threaded Execution:** Speeds up the checking process with up to 200 concurrent threads.
- 🛠️ **Customizable Settings:** Easily adjust the number of threads and other parameters.

## 🛠️ **Installation & Setup**

1. **Install Dependencies:**
   Make sure you have Python 3.x installed. Then, install the required packages using the following command:
   pip install -r requirements.txt
   
2. **Prepare Your Tokens:**
   Create a file named `tokens.txt` in the same directory as the script. List each token on a new line in the format:
   email:password:token
   
3. **Run the Script:**
   Execute the script using Python:
   python ultimate.py
   
4. **Check Results:**
   - **`output/boost1boosts.txt`** - Tokens with 1 boost left.
   - **`output/boost2boosts.txt`** - Tokens with 2 boosts left.
   - **`output/nonitro.txt`** - Tokens without Nitro.
   - **`output/locked.txt`** - Locked tokens.
   - **`output/invalid.txt`** - Invalid tokens.


## 📈 **Usage Example**

python ultimate.py

Once the script completes, it will display a summary of the results and save the categorized tokens to the `output` directory.

## 💬 **Contact & Support**

For questions or support, feel free to reach out via Discord: `termwave_`.

**Happy checking and enjoy your Discord boosts!** 🎉




