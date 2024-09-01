# DNS-Observer
A handy DNS service written in Go to aid in the detection of several types of blind vulnerabilities. It monitors a pentester's server for out-of-band DNS interactions and sends notifications with the received request's details via Slack. DNSObserver can help you find bugs such as blind OS command injection, blind SQLi, blind XXE, and many more!
