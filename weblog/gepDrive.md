---
Date: 2025-04-13 11:19
Type: Page
Title: gepDrive
Location: /gepDrive
---

Redirecting to gd.tchfoo.com/gepDrive...

<script>
function redirectToSubdomain() {
  const redirectBase = 'https://gd.tchfoo.com';
  const redirectPrefixes = ['/gepDrive/', '/auth/', '/header/'];
  const pathname = window.location.pathname;

  for (const prefix of redirectPrefixes) {
    if (pathname.startsWith(prefix)) {
      const newUrl = `${redirectBase}${pathname}${window.location.search}${window.location.hash}`;
      if (window.location.origin !== redirectBase) {
        window.location.replace(newUrl);
      }
      return; // Stop further execution
    }
  }
}
redirectToSubdomain();
</script>