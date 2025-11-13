🔡 Wordlist-Tool

A flexible Python CLI tool for generating wordlists from user‑defined inputs.It supports permutations, product combinations, separators, and OR‑options, making it useful for automation, security research, or custom scripting.

📦 Installation

From PyPI:

pip install wordlist-tool

From source:

git clone https://github.com/RMNO21/wordlist-tool.git
cd wordlist-tool
pip install .

🚀 Usage

After installation, run:

wordlist-tool

The tool will:

Ask you to enter possible words (you can use , for OR options).

Let you specify the loop number (between 1 and 10).

Ask for a separator (optional).

Generate all permutations and product combinations.

Example Run

enter the possible words
enter the possible words (use ',' for OR options)
print <done> or when blank, press <enter> to complete
1: admin,user
2: pass,1234
3: done
enter the loop number: 2
enter the separator, like '@' , '$' , '&' ... : (press enter to fill blank)

Output:

admin@pass
admin@1234
user@pass
user@1234
pass@admin
1234@admin
...

⚙️ Features

Accepts multiple word inputs with OR options (word1,word2)

Generates permutations up to user‑defined loop count

Supports custom separators (@, $, &, etc.)

Prints results directly to stdout (redirect to file if needed)

🛠 Development

Editable install for development:

pip install -e .

Run tests:

pytest

📜 License

This project is licensed under the GNU General Public License v2.0 or later.See the LICENSE file for details.

🤝 Contributing

Pull requests are welcome!For major changes, please open an issue first to discuss what you’d like to change.
