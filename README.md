# Vapsolo Sixer - WebRTC Puller

⚠️ DISCLAIMER: This tool is provided for educational and defensive research purposes only. It demonstrates WebRTC IP leakage, client-side network reconnaissance, and Discord webhook exfiltration techniques. **Unauthorized use against third parties without explicit consent is illegal.** The creator does not take any responsibility for the troubles you get in / the damages you caused with this.

This script (Vapsolo Sixer) was made with JavaScript.

With this script, you can get the other person's IP, Port and information, such as:

- **Region**
- **City**
- **Postal Code**
- **Coordinates**
- **Time zone**
- **ISP**
- **IPv4:Port**
- **IPv6:Port**
- **Ping**

You have 4 buttons in this script's "box" - UDP-Koid(1), Webhook(2), IP address(es) copy(3), Save log(4).

**(1):**

UDP-Koid is a DoS tool where if provided the specific command*, it starts to flood the other person's ipv4 address on that specific UDP port, which causes degradation in their camera quality, and their latency (voice, ping, etc). 

⚠️ **IMPORTANT NOTE:** The UDP-Koid script isn't included with this for obvious reasons - I don't want anyone to DoS anyone with it on OmeTV for fun, and we didn't mention revenge yet. DoS-ing isn't cool, please don't do it.

*: udp-koid <ipv4> <udp-port> <duration(in sec)>

**(2):**

Webhook is what you have to provide in the beginning of the script.
*"const DISCORD_WEBHOOK_URL = "https://discord.com/api/webhooks/YOUR_ID/YOUR_TOKEN";"*

If you provide it, and press "Webhook", it'll embeds the message, and send the person's data you grabbed in through a specific webhook to a specific discord text channel. 

**(3):**

It copies the other person's IPv4 and IPv6 addresses, without the ports, using this specific format:

IPv4: <ipv4>, IPv6: <ipv6>

**(4):**

Saves the log written in a .txt file, containing what people you grabbed in during your session.

# KEYBINDS:

1. Ctrl + C = Copy IPv4
2. Ctrl + F = Copy Port
3. P = Copy UDP-Koid Command

# HOW TO INJECT THIS INTO A WEB BROWSER (ON OmeTV, Omegle, Chat alternative):

1. You open OmeTV / Omegle / Chatalternative in your browser, on your PC / Laptop,
2. You Press F12,
3. Search for a tab called Console, then click on it,
4. When you first try to paste the script into the console, it'll warn you with this:
***"Warning: Don't paste code into the DevTools Console that you don't understand or haven't reviewed yourself. This could allow attackers to steal your identity or take control of your computer. Please type ‘allow pasting’ below (don't press Enter) to allow pasting."***
Type in "allow pasting" , press enter,
5. Paste in the script, and press Enter.

When you inject it, two console warns should pop up:

⚠️ made by: 95.benedek._ (Koid), have fun using it! ;)
⚠️ Discord: 95.benedek._

If you see THAT, that means you successfully injected it, and it's ready to use. You can drag it around wherever you want to put it. 
After it, Press "Start" (in OmeTV / Chatalternative / Omegle), and it'll start to work.

Use it on your own responsibility. The UDP-Koid part will not be released for a while, because I don't want people to DoS eachother.
If you have any more questions, or how to inject this tool into your WEB browser on your PC/Laptop, please contact me on:

**DISCORD**.: 95.benedek._
