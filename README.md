# Time Management AI Assistant

## Setup
1. Clone the repo
```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Create `.env` file with your OpenAI API key
```
OPENAI_API_KEY=your_key_here
```

4. Run the script
```bash
python main.py
```

## Current Features
- PDF upload and analysis
- Question generation from lecture slides

## TODO
- [ ] Web interface
- [ ] Answer grading
- [ ] Weakness tracking
- [ ] User memory/history

## Download Requirements 
pip install -r requirements.txt

## To Run
open two terminals
cd into backend run uvicorn app:app --reload --port 8080
cd into frontend run python -m http.server 8080

## Team
- Andy Huynh
- Ben Fukuzawa
- Shouei Tong
