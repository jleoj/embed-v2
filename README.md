## Website Embedder Pre-release (PROOF OF CONCEPT ONLY!!)

It all started with the dumbest Proof-of-Concept ever and somehow Securly is dumb enough to not be able to block it.
Title says it all, embeds a given URL within an <iframe> and displays it. Comes with a fullscreen button, and cloaking too!

There is a panic key, you have to configure it though. Check the code and replace `https://example.com` with whatever you want to redirect it to. Pressing Ctrl+Shift will trigger the redirect, you can change this as well with keys like `meta` and `alt`

Here are some confirmed working websites:
    https://xc.com/
    https://krunker.io
    *Basically all the io games work*

**reason why not all websites work**
Most websites have a HTTP header called X-Frame-Options, and if they set it to `DENY`, then we can't embed it inside of iframes.

Tested only on Securly for Chromebook MV3 devices. If you confirm this to work on any other blocker, like GoGuardian, Blocksi, etc. please create a PR confirming it with a screenshot/recording.

ABSOLUTELY NO WARRANTY is provided for this, it is only a proof after all, do not create issues spamming with errors. I am aware that the buttons do not work in fullscreen mode (when you press the 5th key left on the Fn top bar on a Chromebook), I might fix it later.

