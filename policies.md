
# very loose

default-src * 'unsafe-inline' 'unsafe-eval'; report-uri /csp-report

# wizard generation

connect-src www.google-analytics.com; img-src www.google-analytics.com; script-src-attr 'unsafe-inline'; script-src-elem 'unsafe-inline' www.google-analytics.com www.googletagmanager.com; script-src 'unsafe-eval'; style-src-attr 'unsafe-inline'; style-src-elem 'unsafe-inline' 

