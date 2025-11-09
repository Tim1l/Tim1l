<!-- Waving Hand GIF for dynamic intro -->
![Waving](rl_trading.gif) 

# 👋 Tim Izmailov – Quant Data Scientist

Passionate data scientist with a nuclear physics background, transitioned into building cutting-edge AI-driven trading systems and generative AI solutions. Developed a high-performance RL trading agent (EV >0.72), a BTC trend predictor (68% accuracy in the trend prediction), and over 500 PineScript strategies, alongside managed portfolio with 25-30% annual returns across last 3 years. Ready to deliver scalable, high-impact AI solutions for quant funds and innovative projects. 🚀

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge)](https://www.linkedin.com/in/tim-izmailov-a53524283/) [![X](https://img.shields.io/badge/X-Follow-black?logo=x&style=for-the-badge)](https://x.com/tim13l) [![Upwork](https://img.shields.io/badge/Upwork-Hire%20Me-green?logo=upwork&style=for-the-badge)](https://www.upwork.com/freelancers/~01d554f7011bd884f2) 

## 🚀 Featured Projects
Star/fork these – sponsors get exclusive models & updates. Hire me on Upwork for custom versions!

<details>
<summary><b>RL Trading Agent for BTCUSDT (EV >0.72)</b> – High-Performance Reinforcement Learning</summary>

**Overview**  
Developed a sophisticated PPO-based reinforcement learning agent for BTC/USD trading on a 15-minute timeframe, leveraging a custom Gym environment with a proprietary reward function. Integrates 80+ high-signal entry points (TP(ATR)=SL(ATR), win rate >60% in backtests) derived from multi-timeframe market patterns (M15, H1, H4, D1).

**Key Features**  
- **Advanced Architecture**: Utilizes a TCN feature extractor (64-256 channels, dilations [1,2,4,8], kernel=10) with action masking for trade compliance.  
- **Performance**: Achieves robust profitability from epoch 1 (32% profit at 10% drawdown in bullish phases).  
- **Scalability**: Optimized for any crypto exchange or MT5 broker without slippage for large enough portfolio.  

**Tech Stack**  
- Python, PyTorch, Stable-Baselines3  
- Custom TCN, Pandas, NumPy, TA-Lib
- Bybit/MT5 APIs for real-time execution  

**Links**  
- *Repo*: [RL BTC Trading Agent](https://github.com/Tim1l/rl-btc-trading-agent)  
- *Monetization*: Contact me to customize this agent for your fund’s trading strategy.  
</details>

<details>
<summary><b>BTC Trend Predictor (68% Accuracy, 0.67 F-Score)</b> – Real-Time Multi-Timeframe Forecasts</summary>

**Overview**  
Built a hybrid TCN-LSTM model with MultiHead Attention for predicting the next candle’s direction across 4h, 1d, and 1w timeframes. Achieves 67-68% accuracy and 0.67 F-score on out-of-sample data, surpassing random baselines by 16-18%, with streaks of 95+ correct predictions.

**Key Features**  
- **Robust Predictions**: Processes high-frequency OHLCV data via CCXT, computing 20 technical indicators (RSI, MACD, Bollinger Bands).  
- **Data Pipeline**: Applies log1p and tanh normalization with rigorous NaN/gap detection and forward-filling for stability.  
- **Deployment**: Runs 24/7, delivering consistent real-time forecasts for multi-timeframe trading.  

**Tech Stack**  
- Python, TensorFlow, Keras-TCN  
- Pandas, TA-Lib, CCXT  

**Links**  
- *Repo*: [Crypto BTC Trend Prediction](https://github.com/Tim1l/crypto_btc_trend_prediction) (currently private)  
- *Engage*: Follow my [X profile](https://x.com/tim13l) for live prediction updates or sponsor for access to the full dataset.  
</details>

<details>
<summary><b>PineScript Strategies (500+ Scripts)</b> – Multi-Timeframe TradingView Systems</summary>

**Overview**  
Crafted 500+ PineScript v6 strategies for TradingView, focusing on multi-timeframe analysis (M15, H1, H4, D1) and market phase decomposition. Includes 80+ core strategies with win rates of 55-75% and sharpe ratio of 1.3-1.8.

**Key Features**  
- **Robust Design**: Utilizes RSI, Bollinger Bands, EMA, HMA, and ATR without curve-fitting for market adaptability.  
- **Multi-Timeframe**: Combines M15 signals with H1/H4/D1 context for high-signal entries.  
- **Customization**: Ready to enhance any trading system with tailored, high-performance strategies.  

**Tech Stack**  
- PineScript v6  

**Links**  
- *Repo*: [PineScript Strategies](https://github.com/Tim1l/PineCryptoStrategies)  
- *Monetization*: Hire me on [Upwork](https://www.upwork.com/services/product/development-it-custom-pine-script-trading-strategy-automated-adjusted-for-profitability-1888093205491441659?ref=project_share) to develop or optimize your trading strategies.  
</details>

<details>
<summary><b>Trading Bots Portfolio (50+ Scripts)</b> – Crypto Futures</summary>

**Overview**  
Designed and deployed 50+ trading bots for BTCUSDT futures, achieving 20-25% annual returns with 10% drawdown while managing a $330K portfolio. Focused on diverse, rigorously backtested trading strategies.

**Key Features**  
- **Performance**: Delivered consistent returns through automated systems optimized for crypto futures.  
- **Backtesting**: Employed rigorous testing to ensure strategy robustness across market conditions.  
- **Experience**: Demonstrates deep expertise in building and managing high-stakes trading systems.  

**Tech Stack**  
- TSLab, Backtrader  

**Details**  
- Showcases my experience in developing and managing automated trading systems for crypto futures.  
</details>

## 🛠️ Skills Stack
A comprehensive set of technical and interpersonal skills honed through advanced AI-driven trading systems, data engineering, and generative AI projects, underpinned by a nuclear physics background that drives analytical precision and problem-solving.

| Category          | Tools & Expertise                                                                 |
|-------------------|----------------------------------------------------------------------------------|
| **AI/ML**         | - **Frameworks**: Proficient in PyTorch, TensorFlow, Keras and Stable-Baselines3 for building and optimizing neural networks and reinforcement learning models. <br> - **Architectures**: Expertise in designing hybrid TCN-LSTM-CNN models with MultiHead Attention and custom feature extractors for time-series prediction. <br> - **Reinforcement Learning**: Advanced PPO implementation with action masking, custom reward shaping, and gradient hooks for stability. <br> - **Model Optimization**: Skilled in dataset preparation, hyperparameter tuning, layer normalization, and optimization to mitigate overfitting and ensure robust performance. <br> - **Predictive Modeling**: Developed models achieving high accuracy and F-scores for financial forecasting. |
| **Trading Systems** | - **Strategy Development**: Expert in crafting robust trading strategies using python, PineScript or TSLAB, with multi-timeframe analysis (M15, H1, H4, D1) and market phase decomposition. <br> - **Automation**: Proficient in Pinescript, TSLab and Backtrader for building automated trading bots, with rigorous backtesting for performance validation. <br> - **API Integration**: Seamless integration with any crypto exchange and MT5 APIs for low-latency execution and real-time market data processing. <br> - **Risk Management**: Skilled in designing systems with dynamic TP/SL and low drawdown strategies for high-stakes environments. <br> - **Market Analysis**: Deep understanding of market phases, technical indicators and multi-timeframe analysis. |
| **Data Engineering** | - **Data Processing**: Advanced proficiency in Pandas, NumPy and Matplotlib for handling high-frequency financial datasets. <br> - **Feature Engineering**: Expertise in computing technical indicators using TA-Lib and implementing robust normalization. <br> - **Time-Series**: Skilled in multi-timeframe data preprocessing, imputation, and quality checks for stable model inputs. <br> - **Data Pipelines**: Built scalable pipelines for real-time OHLCV data fetching and processing. <br> -  **Performance Optimization**: Optimized data workflows for high-throughput environments, achieving high FPS on GPUs across parallel environments. |
| **Generative AI** | - **Leadership**: CTO at FlirtAGPT, driving the development of innovative AI products for conversational and creative applications. <br> - **Model Design**: Experienced in building and deploying generative AI models, leveraging deep learning frameworks for scalable solutions. <br> - **Product Development**: Skilled in end-to-end AI product lifecycle, from ideation to production deployment, with a focus on user-centric outcomes. <br> - **Innovation**: Applied cross-disciplinary insights from trading and physics to create novel generative AI use cases. |
| **Soft Skills**    | - **Analytical Thinking**: Leveraged nuclear physics background to tackle complex problems with precision and rigor. <br> - **Problem-Solving**: Developed innovative solutions for trading and AI challenges, balancing performance and scalability. <br> - **Communication**: Effectively translate technical concepts to stakeholders, as demonstrated in client engagements on Upwork and X posts. <br> - **Adaptability**: Successfully transitioned from nuclear physics to data science, mastering diverse tech stacks and domains. <br> - **Collaboration**: Open to partnerships with quant funds and startups, with a track record of delivering tailored solutions. |

## 📊 Career Timeline
My journey from nuclear physics to data science, building innovative AI-driven trading systems and generative AI solutions:

- **2021**: Developed first predictive model for gold trend forecasting and built initial forex trading bot, laying the foundation for automated trading systems.  
- **2022–2023**: Created and managed a TSLab portfolio with 50+ unique algorithms, focusing on crypto futures and rigorous backtesting for performance.  
- **2023–2024**: Designed hundreds of PineScript v6 strategies for TradingView and advanced predictive models, emphasizing multi-timeframe analysis and robust forecasting.  
- **2025**: Engineered a high-performance RL trading agent and a state-of-the-art predictive model, deployed in real-time for BTCUSDT trading.

## 📈 GitHub Activity & Contributions
Beyond coding, I actively contribute to the developer community:

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Tim1l&show_icons=true&theme=radical&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Tim1l&layout=compact&theme=radical&hide_border=true)

**What I Do Beyond Code:**
- 🌟 **Open Source Sharing**: Publish high-quality projects with detailed documentation and real-world applications
- 📝 **Technical Documentation**: Write comprehensive READMEs with clear setup instructions, architecture diagrams, and use cases
- 🔍 **Code Reviews**: Provide thoughtful feedback on pull requests in trading and ML communities
- 💬 **GitHub Discussions**: Engage in technical discussions about RL, trading strategies, and ML architectures
- 📚 **Knowledge Sharing**: Share insights on [X/Twitter](https://x.com/tim13l) about market predictions and AI developments
- 🎯 **Issue Management**: Maintain clear issue templates and respond promptly to community questions
- 🏆 **Project Showcasing**: Create visual demos (GIFs, charts) to make technical work accessible

## 🤝 Community Engagement & Professional Development

### Active Learning & Sharing
- **Continuous Learning**: Stay current with latest RL techniques, trading strategies, and ML architectures
- **Real-World Application**: Deploy models in production environments, sharing lessons learned
- **Mentoring**: Open to guiding aspiring quant developers through [Upwork](https://www.upwork.com/freelancers/~01d554f7011bd884f2) collaborations
- **Transparency**: Share both successes (68% accuracy) and realistic metrics (drawdowns, win rates)

### Building Professional Reputation
- **Consistent Updates**: Regular commits and project updates demonstrate active development
- **Quality Over Quantity**: Focus on impactful, well-documented projects rather than numerous small repos
- **Professional Profile**: Maintain clear bio, professional photo, and comprehensive project descriptions
- **Cross-Platform Presence**: LinkedIn for professional networking, X for technical insights, Upwork for client work
- **Monetization Options**: GitHub Sponsors for exclusive access, encouraging community support

### Best Practices I Follow
- ✅ Write clean, commented code with proper version control
- ✅ Include comprehensive READMEs with problem statement, solution, and results
- ✅ Add badges for quick project status visibility (accuracy, performance metrics)
- ✅ Use GitHub Projects and Issues for transparent development tracking
- ✅ Pin best repositories to profile for immediate visibility
- ✅ Keep projects updated with recent activity and maintenance
- ✅ Respond to community engagement (stars, forks, questions)

## 💡 How to Build Your GitHub Professional Brand (Beyond Code)
*Actionable steps for developers looking to promote themselves as professionals on GitHub:*

### 1. **Profile Optimization**
- ✨ Create a README profile repository (username/username) with your bio, skills, and showcase projects
- 🖼️ Add a professional photo and complete bio with your expertise areas
- 🔗 Link all professional profiles (LinkedIn, X/Twitter, personal website, portfolio)
- 📍 Add location and availability for work/collaboration

### 2. **Documentation Excellence**
- 📝 Write detailed READMEs for every project (problem, solution, tech stack, results, setup instructions)
- 🎥 Add GIFs, screenshots, or videos demonstrating your projects in action
- 📊 Include performance metrics, benchmarks, and real-world results
- 🏗️ Create architecture diagrams and flowcharts for complex systems
- 📚 Add CONTRIBUTING.md, CODE_OF_CONDUCT.md for community projects

### 3. **Visual & Metrics Enhancement**
- 🏅 Use shields.io badges to show build status, test coverage, version, downloads
- 📈 Add GitHub stats widgets to your profile README
- 🎯 Create custom badges showcasing your key metrics (accuracy, performance, returns)
- 📷 Pin your 6 best repositories to your profile for immediate visibility

### 4. **Community Engagement**
- 💬 Participate in GitHub Discussions in your domain
- 🔍 Contribute to open-source projects (even small PRs help build reputation)
- ⭐ Star and fork projects you find valuable, engage with their communities
- 🐛 Report issues with clear reproduction steps and proposed solutions
- ✅ Review pull requests and provide constructive feedback

### 5. **Consistent Activity**
- 📅 Maintain a green contribution graph with regular commits
- 🔄 Update projects with improvements, bug fixes, and new features
- 📰 Use GitHub Releases to announce major updates
- 🏷️ Add relevant topics/tags to repositories for discoverability
- 🗓️ Keep projects maintained (respond to issues within reasonable time)

### 6. **Professional Showcase**
- 🎯 Focus on quality over quantity – fewer excellent projects beat many mediocre ones
- 🌟 Highlight real-world impact: user metrics, business value, performance improvements
- 📖 Write blog posts or technical articles about your projects (link from README)
- 🎤 Give talks or create video tutorials about your work
- 💼 Add case studies showing problem-solving approach and results

### 7. **Networking & Opportunities**
- 🤝 Enable GitHub Sponsors for monetization opportunities
- 💰 Offer consulting services (link to Upwork, Toptal, or personal site)
- 🔗 Cross-promote on LinkedIn, X/Twitter with your GitHub work
- 📧 Add contact information for collaboration opportunities
- 🌐 Build a personal brand across platforms with consistent messaging

### 8. **Technical Credibility**
- 🔒 Follow security best practices (no hardcoded credentials, use .gitignore)
- ✅ Add CI/CD pipelines (GitHub Actions) showing automated testing
- 📦 Publish packages to npm, PyPI, or other registries
- 🧪 Include test coverage and quality metrics
- 📜 Choose appropriate open-source licenses

### 9. **Specialization & Authority**
- 🎓 Showcase domain expertise (AI/ML, trading systems, specific frameworks)
- 🏆 List certifications, courses, or achievements in your profile
- 📊 Create comparison benchmarks with existing solutions
- 🔬 Share research, papers, or novel approaches
- 💡 Solve real problems with practical, deployable solutions

### 10. **Long-term Strategy**
- 🎯 Define your niche and become known for specific expertise
- 📈 Track your profile views and engagement metrics
- 🔄 Regularly update your profile with latest achievements
- 🌱 Help others learn through examples, tutorials, and mentoring
- 🚀 Build a portfolio that tells a story of your professional growth

**Remember**: GitHub is not just a code storage – it's your living portfolio, professional network, and opportunity platform. Every commit, PR, issue, and discussion contributes to your professional brand!

## 🤝 Connect & Collaborate
I’m passionate about building cutting-edge AI trading systems and generative AI solutions. Let’s create value together!

- **Quant Funds & Startups**: Partner with me to develop scalable, high-impact trading algorithms and AI models. DM on [LinkedIn](https://www.linkedin.com/in/tim-izmailov-a53524283/) or [X](https://x.com/tim13l).  
- **Custom Solutions**: Hire me on [Upwork](https://www.upwork.com/freelancers/~01d554f7011bd884f2) for tailored RL agents, predictive models, or trading strategies.  
- **Sponsorship**: Gain early access to exclusive models and datasets – [Sponsor Now](https://github.com/sponsors/Tim1l).  

Star my repos to stay updated on the latest AI trading innovations! 🚀  
![BTC Predictor](https://img.shields.io/badge/BTC%20Predictor-68%25%20Accuracy%20%7C%200.67%20F--Score-green?style=for-the-badge) ![RL Agent](https://img.shields.io/badge/RL%20Agent-EV%200.72%20%7C%2032%25%20Profit-blue?style=for-the-badge)
[![Sponsor Me](https://img.shields.io/badge/Sponsor-Me-ff69b4?style=for-the-badge&logo=github-sponsors&logoColor=white)](https://github.com/sponsors/Tim1l)
