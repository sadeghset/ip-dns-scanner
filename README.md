# IP & DNS Scanner

A web-based application for scanning clean IPs and DNS servers with speed and ping measurement capabilities.

## Features

- 🌐 **IP Scanner**: Scan and test public IPs
- 🔍 **DNS Testing**: Check DNS servers for reliability
- ⚡ **Speed Measurement**: Measure response time and latency
- 📊 **Ping Test**: Test connectivity with ICMP ping
- 📱 **Responsive UI**: Works on desktop and mobile devices
- 📈 **Real-time Results**: See results as they are being processed
- 💾 **Export Results**: Save results for later analysis

## Project Structure

```
ip-dns-scanner/
├── index.html              # Main HTML entry point
├── style.css               # Styling
├── app.js                  # Main application logic
├── modules/
│   ├── ipScanner.js        # IP scanning module
│   ├── dnsChecker.js       # DNS checking module
│   ├── networkTester.js    # Network testing module
│   └── ui.js              # UI management
├── data/
│   ├── dns-servers.json   # Common DNS servers
│   └── ip-ranges.json     # IP ranges to test
└── README.md              # Documentation
```

## Usage

1. Open `index.html` in your browser
2. Select the type of scan (IP or DNS)
3. Configure scan parameters
4. Start the scan
5. View results in real-time
6. Export results if needed

## Installation

```bash
git clone https://github.com/sadeghset/ip-dns-scanner.git
cd ip-dns-scanner
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- No external dependencies required

## License

MIT
