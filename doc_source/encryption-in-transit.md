# Encryption in transit<a name="encryption-in-transit"></a>

Encryption in transit refers to protecting your data from being intercepted while it moves between communication endpoints\. Amplify Console provides encryption for data in\-transit by default\. All communication between customers and Amplify and between Amplify and its downstream dependencies is protected using TLS connections that are signed using the Signature Version 4 signing process\. All Amplify Console endpoints use SHA\-256 certificates that are managed by AWS Certificate Manager Private Certificate Authority\. For more information, see [Signature Version 4 signing process](https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html) and [What is ACM PCA](https://docs.aws.amazon.com/acm-pca/latest/userguide/PcaWelcome.html)\.