# website

How to get new laptop with **OS X 10.13.5 and Xcode 9.3 (9E145)** to run this project

https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

1. this fixed nokogiri install 

    https://github.com/sparklemotion/nokogiri/issues/1483

    (http://www.nokogiri.org/tutorials/installing_nokogiri.html#mac_os_x)

        brew unlink xz && sudo gem install nokogiri -v '1.8.3' --source 'https://rubygems.org/' &&
        

1. `gem install bundler`

1. in this repository directory run 

        $ bundle install

1. 

