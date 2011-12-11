Android and self-signed ssl certificates
========================================

Dealing with self-signed ssl certificates is a real pain, because it’s not that simple to add them in your app and let android accept them.
But fortunately, there’s a workaround that uses an own SSLSocketFactory and an own TrustManager. With this, only your added site is beeing able to be called, so theres no security issue.
