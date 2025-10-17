# 🌐 Datagram Alpha Testnet Node - NodeOps Template

![Datagram Logo](assets/datagram-logo.png)

Deploy a Datagram Alpha Testnet node on NodeOps and earn points for future $DGRAM tokens!

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![NodeOps](https://img.shields.io/badge/NodeOps-Compatible-brightgreen)](https://cloud.nodeops.network/marketplace)
[![Testnet](https://img.shields.io/badge/Testnet-Alpha-orange)](https://demo.datagram.network/account)

## 📖 What is This?

This is a NodeOps template that lets you deploy a **Datagram Alpha Testnet Full Core node** with just one click. By running this node, you'll earn **non-transferable points** based on uptime and network usage. These points may influence future $DGRAM token allocation when mainnet launches.

### ✨ Features

- 🚀 **One-Click Deployment** - Just provide your license key
- �� **Cost-Efficient** - Minimal resources (200m CPU, 256MB RAM) = <$10/month
- 🔒 **Secure** - Runs as non-root user in Alpine Linux container (35.5MB)
- 📈 **Earn Rewards** - Points accumulate 24/7 based on uptime and usage
- 🔄 **Auto-Recovery** - Automatic restarts on failure
- 📊 **Easy Monitoring** - Track earnings in Datagram dashboard

## 🚀 Quick Start

### Step 1: Get Your Datagram License Key
Use my referral code: https://demo.datagram.network?ref=228585884
1. Visit [demo.datagram.network/account?tab=apis](https://demo.datagram.network/account?tab=apis)
2. Create your account and generate API key
3. Visit [demo.datagram.network/wallet?tab=licenses](https://demo.datagram.network/wallet?tab=licenses)
4. Generate your license key
5. **Save it securely** - you'll need it for deployment

### Step 2: Deploy on NodeOps

1. Log in to [NodeOps Marketplace](https://cloud.nodeops.network/marketplace)
2. Search for **"Datagram Alpha Testnet Node"**
3. Click **"Deploy"**
4. Enter your **DATAGRAM_LICENSE_KEY**
5. (Optional) Customize **NODE_NAME** and **LOG_LEVEL**
6. Click **"Deploy"**

### Step 3: Monitor Your Node

- **Wait**: Allow 5-10 minutes for initial sync and connection
- **Check Dashboard**: Go to [demo.datagram.network/overview](https://demo.datagram.network/overview)
- **Track Points**: View your **TOTAL ALPHA TESTNET EARNINGS**

⚠️ **Important**: Points may not appear immediately! Your participation is being tracked, and most points will be distributed once the system stabilizes. It's normal to see zero points for 24+ hours.

## �� What You're Running

- **Image**: Datagram CLI v1.1.4
- **Resources**: 200m CPU (0.2 cores), 256MB RAM
- **Node Type**: Full Core (maximum earning potential)
- **Cost**: <$10/month on NodeOps
- **Uptime Goal**: 99%+ for maximum rewards

## 💰 How Earnings Work

### Points System
- Earn **non-transferable points** during Alpha Testnet
- Points based on:
  - ✅ **Uptime & Availability** - Keep your node online
  - ✅ **Actual Usage** - Bandwidth, compute contributions
  
### Future Rewards
- Points may influence $DGRAM token allocation when mainnet launches
- **No guaranteed value** - testnet participation only
- Early participation benefits from established network effects

## 🔧 Configuration Options

| Variable | Default | Description |
|----------|---------|-------------|
| `DATAGRAM_LICENSE_KEY` | **(required)** | Your Datagram license key |
| `NODE_NAME` | `nodeops-datagram` | Custom name for your node |
| `LOG_LEVEL` | `info` | Logging level (debug, info, warn, error) |

## 📈 Expected Performance

- **Startup Time**: 5-10 minutes for initial sync
- **CPU Usage**: ~5-50m actual (0.005-0.05 cores)
- **Memory Usage**: ~150-256MB RAM
- **Network**: Variable based on traffic routed
- **Uptime**: Runs 24/7 on NodeOps infrastructure

## ❓ Troubleshooting

### Node Not Showing in Dashboard
- **Wait longer**: Initial sync can take 5-10 minutes
- **Check license key**: Ensure it's valid and correctly entered
- **Check logs**: View container logs in NodeOps dashboard

### Zero Points Earned
- **Give it time**: Points accumulate based on actual network usage
- **Verify connection**: Node must fully sync before earning
- **Check uptime**: Higher uptime = more earning opportunities

### Container Restarting
- Usually normal during initial sync
- Check NodeOps logs for specific errors
- Verify license key is valid

## 🌐 Useful Links

- **Datagram Account Dashboard**: [demo.datagram.network/account](https://demo.datagram.network/account)
- **Datagram Overview**: [demo.datagram.network/overview](https://demo.datagram.network/overview)
- **NodeOps Marketplace**: [cloud.nodeops.network/marketplace](https://cloud.nodeops.network/marketplace)
- **Tutorial**: See [TUTORIAL.md](TUTORIAL.md) for detailed guide
- **Support**: Contact via [Telegram](https://t.me/Cerebro_Virgil) or [Twitter](https://x.com/Cerebro_Agent)

## 📄 License

This template is provided as-is under the MIT License. See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- **Datagram Team** - For building the Global Hyper-Fabric Network
- **NodeOps** - For providing the deployment platform
- **Alpha Testnet Participants** - For helping build the future of decentralized infrastructure

---

**Ready to start earning?** Deploy now on [NodeOps Marketplace](https://cloud.nodeops.network/marketplace)!
