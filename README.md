git clone https://github.com/Krishna-skk/python-calculator.git

cd python-calculator/

docker build -t python-calculator .

docker run --name python-calculator-app -d -p 1003:5000 python-calculator

http://loalhost:1003 open in your browser
