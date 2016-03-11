**Sontana** (สนทนา) is a chatbot written in [Python](http://www.python.org) built on top of [Cobe](http://github.com/pteichman/cobe) running on Jabber ([xmpppy](http://xmpppy.sourceforge.net/)). The main language of the bot is, absolutely, Thai.

**Requirements**
  * [Python](http://python.org) 2.6.x or great
  * [XMPPPY](http://xmpppy.sourceforge.net/) - the jabber python
  * [Cobe](http://github.com/pteichman/cobe) - a conversation simulator, a database backed port of MegaHAL
  * [SWATH](http://www.cs.cmu.edu/~paisarn/software.html) - Thai Word Segmentation
  * Jabber account, e.g. [Google talk](http://www.google.com/talk/)

**Current released**: There is no binary files released now. Please checkout SVN:
```
svn checkout http://sontana.googlecode.com/svn/trunk/ sontana-read-only
```

**Installation**
  1. Get source code from SVN as mentioned above
  1. Run the script using command `./jabberbot.py robot@jabbberserver.com #you will be prompt to enter the password`
  1. You can chat with your robot by adding robot@jabbberserver.com to your separated jabber account. The robot will accept every invitation automatically.
**Note**: At the first glance, the robot will have not enough knowledge to reply to your question. However, it will add the knowledge to its brain from your input. As much as you talk to it, the better conversation you will obtain. The robot memory will be stored in the brain.db file persistently. If this file does not exist, the new fresh blank brain will be initiated.

**Open-source License**: [MIT](http://www.opensource.org/licenses/mit-license.php)