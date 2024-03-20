$ pip install challenge-cli
$ git clone git@github.com:architv/chcli.git
$ cd chcli
$ python setup.py install

$ challenges --active
$ challenges --active -p HR -p TC # get active challenges from HackerRank(HR) and topcoder(TC).
$ challenges --upcoming
$ challenges --active 1 # opens the first active challenge in your browser
$ challenges --upcoming -p HR -p TC # HR and TC are platform code for HackerRank and TopCoder Respectively
$ challenges --short -p CF # get all the short challenges from codeforces
$ challenges --hiring # get all the hiring challenges
$ challenges -t 2 # get all the active challenges and upcoming challenges which start in the next 2 days
