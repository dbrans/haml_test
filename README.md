## Installation

1. Install nodejs
http://nodejs.org/download/

1. Install compass 
```
gem update --system
gem install compass
```

1. Install grunt
```
npm install -g grunt-cli
```

1. Install HAML
```
gem install haml
```

1. Clone the repo and install packages
```
git clone https://github.com/dbrans/haml_test
cd haml_test
npm install && bower install --dev
```

## Getting started
1. Run the server: ```grunt server```. This will open a browser window.
2. Edit ```app/index.haml``` and save. This should refresh the browser window.
