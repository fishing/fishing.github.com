# Note: github-pages depends on nokogiri but it's stupid and fails to use system
# libraries without flags. Here's how to do it for OS X using MacPorts & brew.
#
# For MacPorts:
# sudo port install libxml2 libxslt
# gem install nokogiri -- --use-system-libraries --with-xml2-config=/opt/local/bin/xml2-config --with-xslt-config=/opt/local/bin/xslt-config
#
# For HomeBrew:
# brew install libxml2 libxslt libiconv
# NOKOGIRI_USE_SYSTEM_LIBRARIES=1 gem install nokogiri -- --use-system-libraries --with-iconv-dir="$(brew --prefix libiconv)" --with-xml2-config="$(brew --prefix libxml2)/bin/xml2-config" --with-xslt-config="$(brew --prefix libxslt)/bin/xslt-config"

# OK we just need github-pages now.
source 'https://rubygems.org'
gem 'github-pages'
