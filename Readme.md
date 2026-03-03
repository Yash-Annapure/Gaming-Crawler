# Gaming Crawler 🕹️

Ever wondered what games are trending on Steam or wanted to build your own game database? This Python crawler does exactly that: it grabs detailed game info from Steam so you can analyze, visualize, or just geek out over gaming data.

**Part of our Data Engineering Pipeline project** – check out how we process thousands of game records in this industry grade system!

```The below project is for Academic purposes Only, we do not encourage web-scraping without explicit required permissions!!```

## 🎬 See It In Action

Watch the crawler pull live data from Steam in real-time:

<div align="center">
  
### [▶️ Watch Demo Video on Google Drive](https://drive.google.com/file/d/1y5krRbNvfwIRX1OEhStGQGyBRu1lJbEI/view?usp=sharing)

*Click above to see the scraper in action (opens in new tab)*

</div>

---

## ✨ What Can You Do With This?

- 📊 **Build your own gaming analytics dashboard** – track price trends, review scores, player counts
- 🔍 **Discover hidden gems** – find underrated games based on reviews and ratings
- 📈 **Market research** – analyze what types of games are popular right now
- 🎓 **Learn web scraping** – perfect beginner-friendly project for data engineering

---

## 🛠️ What You'll Need

Just a few things before we get started:

- **Python 3.8 or newer** – [grab it here](https://www.python.org/downloads/) if you don't have it
- **pip** – this comes bundled with Python, so you're probably good
- **uv** – a fast Python package manager (we'll install this together)

---

## 🚀 Let's Get This Running

### Step 1: Install uv (the easy way)

Open your terminal and run:

```bash
pip install uv
```

*Having trouble? Try `pip install uv --user` if you get permission errors*

### Step 2: Grab the code

```bash
git clone <your-repo-url>
cd gaming_crawler
```

### Step 3: Set everything up

```bash
cd Scripts
uv sync
```

This will install all the dependencies you need. Takes about 30 seconds.

### Step 4: Fire it up! 🎮

```bash
python steam_scraper.py
```

Boom! You should see the scraper start pulling game data from Steam.

---

## 💡 What Happens Next?

Once you run the script, you'll see:
- Game titles, prices, and release dates being fetched
- Review scores and player counts
- All data saved locally (check the output folder)

**Pro tip:** The first run might take a few minutes depending on how much data you're scraping. Grab a coffee ☕

---

## 🤔 Common Questions

**Q: Why isn't the demo video loading?**  
A: The video is on Google Drive. You might need to request access if you're not logged in or if permissions aren't set to "Anyone with the link."

**Q: Do I need a Steam API key?**  
A: Nope! This scraper works right out of the box.

**Q: Can I scrape other gaming platforms?**  
A: Ya Currently it can Scrape 3 different Dynamic websites, you can modify the code as you wish

**Q: Is this legal?**  
A: Yes, for personal projects and research. Just don't abuse it – respect Steam's rate limits and robots.txt.

---

## 🐛 Running Into Issues?

**"Python not recognized" error:**  
- Make sure Python is added to your system PATH during installation
- On Windows: Re-run the Python installer and check "Add Python to PATH"

**"Permission denied" when installing uv:**  
- Try: `pip install uv --user`
- Mac/Linux: Might need `sudo pip install uv`

**Scraper not finding data:**  
- Check your internet connection
- Steam might be temporarily blocking requests – wait a bit and try again

---

## 🎯 What's Next?

Once you've got data flowing:
1. **Explore the data** – open up the CSV/JSON files and see what you've collected
2. **Build visualizations** – throw it into pandas, matplotlib, or your favorite BI tool
3. **Automate it** – set up a cron job to scrape daily and track changes over time
4. **Share your findings** – found something cool? We'd love to see it!

---

## 🤝 Want to Contribute?

Got ideas for new features? Found a bug? PRs are welcome! This project is all about learning and building cool stuff together.

---

**Happy scraping, and may your datasets be ever clean! 🎮✨**

---

*Built with ❤️ by data nerds who love gaming*
