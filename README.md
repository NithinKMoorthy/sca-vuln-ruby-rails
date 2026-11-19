# sca-vuln-ruby-rails

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** RubyGems (Bundler)

## Expected findings (non-exhaustive)
- rails/actionpack 5.2.0: CVE-2019-5418 (file disclosure), CVE-2020-8164
- nokogiri 1.10.3: CVE-2019-5477, CVE-2020-26247
- rack 2.0.6: CVE-2019-16782, CVE-2020-8184
- devise 4.6.0: CVE-2019-16109
- puma 3.12.0: CVE-2019-16770, CVE-2020-5247
- loofah 2.2.2: CVE-2018-16468
- rubyzip 1.2.1: CVE-2018-1000544
