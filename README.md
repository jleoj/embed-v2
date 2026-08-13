## Website Embedder Pre-release (PROOF OF CONCEPT ONLY)

There is a panic key, you have to configure it though. Check the code and replace `https://example.com` with whatever you want to redirect it to. Pressing Ctrl+Shift will trigger the redirect, you can change this as well with keys like `meta` and `alt`

Here are some confirmed working websites:
    https://xc.com/
    https://krunker.io
    *Basically all the io games work*

**reason why not all websites work**
Most websites have a HTTP header called X-Frame-Options, and if they set it to `DENY`, then no more iframe (this is for good security reasons)

Tested only on Securly for Chromebook MV3 devices. If you confirm this to work on any other blocker, like GoGuardian, Blocksi, etc. please create a PR confirming it with a screenshot/recording.

ABSOLUTELY NO WARRANTY is provided for this, it is only a proof after all, do not create issues spamming with errors. I am aware that the buttons do not work in fullscreen mode (when you press the 5th key left on the Fn top bar on a Chromebook), I might fix it later.

