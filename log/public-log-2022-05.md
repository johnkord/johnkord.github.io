# Public Log 2022-05
## Article
Name: Everything you should know about certificates and PKI but are too afraid to ask 
URI: https://smallstep.com/blog/everything-pki/
Archive URI: https://web.archive.org/web/20220510095613/https://smallstep.com/blog/everything-pki/

Most engineers I've met don't have an understanding of PKI and therefore don't understand how to enable TLS in their own projects. The first time I encountered PKI in my career was when a certificate expired that my team was relying on, and we had to get a new one. No one on my team knew how to do this, so it was up to me to figure it out. At some point all software engineers will probably be in the same boat.

Along with this article, I also strongly recommend becoming familiar with the `openssl x509 -in CERT.pem -text` command for the ability to diagnose PKI issues. (Also other `openssl` subcommands for other PKI assets like CRLs and CSRs)
