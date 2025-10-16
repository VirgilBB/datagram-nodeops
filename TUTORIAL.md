# 📚 Datagram Alpha Testnet Node - Deployment Tutorial

Complete guide to deploying and managing your Datagram Alpha Testnet node on NodeOps.

## Table of Contents

1. [Before You Start](#before-you-start)
2. [Getting Your License Key](#getting-your-license-key)
3. [Deploying on NodeOps](#deploying-on-nodeops)
4. [Monitoring Your Node](#monitoring-your-node)
5. [Understanding Rewards](#understanding-rewards)
6. [Troubleshooting](#troubleshooting)

---

## Before You Start

### What You Need

✅ **Account on NodeOps** - [Sign up here](https://cloud.nodeops.network/marketplace)  
✅ **Datagram License Key** - We'll get this in Step 1  
✅ **5 minutes** - That's it!

### What You'll Get

📈 **Points for Future Tokens** - Non-transferable points that may influence $DGRAM allocation  
🌐 **Network Participation** - Help power the Datagram Global Hyper-Fabric Network  
💻 **Learning Experience** - Understand DePIN and decentralized infrastructure

---

## Getting Your License Key

### Step 1: Create Datagram Account & API Key

1. Visit [demo.datagram.network/account?tab=apis](https://demo.datagram.network/account?tab=apis)
2. Click **"Sign Up"** or **"Create Account"**
3. Complete registration
4. Navigate to the **"APIs"** tab
5. Generate your API key
6. **Save it securely** - you'll need this for account management

### Step 2: Get Your License Key

1. Visit [demo.datagram.network/wallet?tab=licenses](https://demo.datagram.network/wallet?tab=licenses)
2. Navigate to the **"Licenses"** tab
3. Generate your license key
4. **Copy your license key** - it will look like a long string of characters
5. **Save it securely** - you'll need this for NodeOps deployment

⚠️ **Important**: Keep your license key private. It's linked to your future rewards!

---

## Deploying on NodeOps

### Step 1: Find the Template

1. Log in to [NodeOps Marketplace](https://cloud.nodeops.network/marketplace)
2. Go to **Templates** section
3. Search for **"Datagram Alpha Testnet Node"**
4. Click on the template to open it

### Step 2: Configure Your Deployment

You'll see a form with these fields:

#### Required Field:
- **DATAGRAM_LICENSE_KEY**: Paste the license key you got from Datagram wallet

#### Optional Fields:
- **NODE_NAME**: Give your node a custom name (default: `nodeops-datagram`)
  - Example: `nodeops-virgil-01` if you want to run multiple nodes
- **LOG_LEVEL**: Keep as `info` unless you need debugging

### Step 3: Deploy!

1. Click **"Deploy"** button
2. Wait for NodeOps to provision your container
3. You'll see a deployment screen with:
   - Container status
   - Resource usage (CPU, Memory)
   - Logs

### Step 4: Initial Sync (Be Patient!)

⏱️ **Allow 5-10 minutes** for:
- Container startup
- Network sync
- Connection establishment
- Metrics reporting to start

You'll see logs like:
```
App version: 1.1.4
Downloading...
Conference version: 1.1.4
Running...
```

✅ This is normal! The node is syncing with the Datagram network.

---

## Monitoring Your Node

### On NodeOps Dashboard

**Resource Usage:**
- **CPU**: Should be very low (~0.005-0.05 cores)
- **Memory**: ~150-256MB
- **Status**: "Running"

**Logs:**
- Check logs for any errors
- Should see "Running..." message
- No red error messages = good!

### On Datagram Dashboard

1. Go to [demo.datagram.network/overview](https://demo.datagram.network/overview)
2. Log in with your Datagram account
3. Look for:
   - **TOTAL ALPHA TESTNET EARNINGS** - Your accumulated points
   - **Network Status** - Should show "CONNECTED" after initial sync
   - **Uptime** - Hours/days your node has been running

### What to Expect

| Metric | Expected Value |
|--------|---------------|
| **Sync Time** | 5-10 minutes initially |
| **Status** | CONNECTED (after sync) |
| **Uptime** | Should increase continuously |
| **Points** | Accumulate based on uptime + usage |
| **CPU Usage** | Very low (~0.005-0.05 cores) |
| **Memory** | ~150-256MB |

---

## Understanding Rewards

### How Points Are Earned

1. **Uptime & Availability**
   - Keep your node online 24/7
   - Higher uptime = more points
   - Target: 99%+ uptime

2. **Actual Usage**
   - Network routes traffic through your node
   - You earn based on bandwidth/compute contributed
   - Variable based on network demand

### What Points Mean

- ⚠️ **Non-transferable** during testnet
- ✅ **Proof of participation** in Alpha Testnet
- 🎯 **May influence** future $DGRAM token allocation
- 💡 **No guaranteed value** - this is testnet participation

### Maximizing Your Points

✅ **Keep node running 24/7** - Consistent uptime is key  
✅ **Monitor regularly** - Check dashboard weekly  
✅ **Don't restart unnecessarily** - Uptime resets on restart  
✅ **Wait for full sync** - Don't worry if points are zero initially  

---

## Troubleshooting

### ❌ Node Stuck on "Downloading..."

**Solution:**
- Wait 5-10 minutes
- This is normal during initial sync
- Check back later - it will progress to "Running..."

### ❌ Dashboard Shows "DISCONNECTED"

**Causes & Solutions:**

1. **Too Soon** - Node hasn't finished syncing yet
   - ✅ Wait 5-10 minutes after deployment

2. **Invalid License Key** - Typo or wrong key
   - ✅ Double-check license key in NodeOps deployment
   - ✅ Verify it matches what's in Datagram wallet

3. **Container Restarted** - May need to resync
   - ✅ Check NodeOps logs for errors
   - ✅ Give it time to reconnect

### ❌ Zero Points Earned

**⚠️ THIS IS COMPLETELY NORMAL!**

According to Datagram team:
> "If you've been running your node for a while without receiving points, that's normal. Most points will be distributed once the system stabilizes. Your participation is being tracked, and you'll receive your points once full distribution begins."

**What this means:**
- ✅ Your node IS being tracked
- ✅ Points will be distributed later when system stabilizes
- ✅ Normal to see zero points for 24+ hours, days, or even weeks
- ✅ Keep your node running to ensure full credit

**What to verify:**
- ✅ Node status shows "CONNECTED" or "Running"
- ✅ Uptime is increasing in Datagram dashboard
- ✅ No errors in NodeOps logs
- ✅ Container is not restarting repeatedly

### ❌ Container Using Too Much Memory

**Normal behavior:**
- Memory usage: 150-256MB is expected
- CPU usage: Very low (~0.005-0.05 cores)

**If memory is higher:**
- Check logs for errors
- May be temporary during sync
- Contact support if consistently above 300MB

### 🆘 Still Having Issues?

**Get Help:**
- 📧 **Email**: Support via NodeOps platform
- 💬 **Telegram**: [t.me/Cerebro_Virgil](https://t.me/Cerebro_Virgil)
- 🐦 **Twitter**: [@Cerebro_Agent](https://x.com/Cerebro_Agent)
- 📖 **Datagram Docs**: [docs.datagram.io](https://docs.datagram.io)

---

## Next Steps

✅ **Deploy your node**  
✅ **Wait for sync (5-10 min)**  
✅ **Check dashboard for points**  
✅ **Monitor weekly**  
✅ **Keep it running 24/7**  

**That's it!** Your Datagram Alpha Testnet node is now earning points while you sleep. Welcome to the future of decentralized infrastructure! 🚀

---

Need help? Contact us via [Telegram](https://t.me/Cerebro_Virgil) or [Twitter](https://x.com/Cerebro_Agent)
