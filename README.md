# AI Agent Earnings Calculator 🤖💰

<p align="center">
  <a href="https://agent-earnings.surge.sh">Live Demo</a> •
  <a href="#features">Features</a> •
  <a href="#deployment">Deployment</a>
</p>

A beautiful, mobile-responsive calculator that estimates potential earnings for AI agents completing bounties on platforms like the [AI Bounty Board](https://bounty.owockibot.xyz).

## Features

### 📊 Comprehensive Calculations
- **Daily/Weekly/Monthly/Yearly** earnings projections
- **Success rate** factoring (not all bounties get accepted)
- **Operating costs** deduction (API fees, hosting, etc.)
- **ROI percentage** on operating costs

### 🆚 Human Comparison
- Side-by-side comparison with freelancer rates
- Junior ($25/hr), Mid ($50/hr), Senior ($100/hr) developer rates
- Visual bar charts for easy comparison
- Highlights the 24/7 advantage of AI agents

### 📱 Mobile Responsive
- Fully responsive design works on all devices
- Touch-friendly sliders
- Clean, modern UI with dark theme

### 📤 Share Results
- One-click share button
- Generates URL with all parameters
- Easy to share your projections with others

## Calculator Parameters

| Parameter | Range | Description |
|-----------|-------|-------------|
| Bounties/Day | 1-20 | Number of bounties your agent attempts daily |
| Avg Bounty Value | $5-$100 | Average USDC reward per bounty |
| Success Rate | 50%-100% | Percentage of submissions accepted |
| Days/Week | 1-7 | Operating days (agents can work 24/7!) |
| Operating Cost | $0-$500 | Monthly API, hosting, and other costs |

## Quick Start

### Local Development
```bash
# Just open index.html in your browser
open index.html

# Or use a local server
npx serve .
```

### Deploy to Surge
```bash
npm install -g surge
surge . agent-earnings.surge.sh
```

### Deploy to Vercel
```bash
npm install -g vercel
vercel --prod
```

### Deploy to Netlify
Just drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)

## Technology

- **Pure HTML/CSS/JS** - No build step required
- **Zero dependencies** - Single file, instant load
- **Modern CSS** - Custom properties, Grid, Flexbox
- **Responsive** - Mobile-first design

## URL Parameters

Share specific configurations using URL parameters:

```
?b=5&v=25&s=85&d=7&c=50
```

| Param | Description |
|-------|-------------|
| `b` | Bounties per day |
| `v` | Average bounty value |
| `s` | Success rate (%) |
| `d` | Days per week |
| `c` | Operating cost |

## Example Scenarios

### Conservative Agent
- 3 bounties/day @ $20 avg
- 80% success rate
- 5 days/week
- **Monthly: ~$1,040**

### Active Agent
- 8 bounties/day @ $30 avg
- 90% success rate
- 7 days/week
- **Monthly: ~$6,500**

### High-Volume Agent
- 15 bounties/day @ $25 avg
- 85% success rate
- 7 days/week
- **Monthly: ~$8,200**

## Screenshots

The calculator features:
- 🎨 Modern dark theme with gradient accents
- 📊 Real-time updating charts
- 💫 Smooth animations
- 📱 Perfect mobile experience

## License

MIT

---

Built by [kevi-ai](https://github.com/kevi-ai) for [AI Bounty Board](https://bounty.owockibot.xyz) Bounty #79
