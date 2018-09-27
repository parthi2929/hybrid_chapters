This is a sample template with script to facilitate mixed chapters from raw tex files and tex files generated from ipython notebooks. 

[Main Demo](http://nbviewer.jupyter.org/github/parthi2929/hybrid_chapters/blob/master/main.pdf)

Update 27th Sept 2018:  
1. tikzmagic demo along with ability to maintain minimum output size (as tikzmagic outputs are small [1](https://tex.stackexchange.com/questions/452720/weird-image-scaling-in-tex)[2](https://github.com/mkrphys/ipython-tikzmagic/issues/27))  
2. hiding cells in tex that are tagged in notebook as 'to_remove'  


Issues:
Major:
1. Wrapping is not proper [ref](https://i.postimg.cc/25CZJF6K/issue_1.jpg). AVoid long code sentence or comments. Also avoid quotes inside comments.
2. Output diagram extends to full width [ref](https://i.postimg.cc/25CZJF6K/issue_1.jpg)
3. Individual pdf for jupyter generated tex file not happening when it has external cross references.
4. Every time script to generate tex from notebook is run, new files  are generated even if already images exist. 

Minor:
1. Code cell also contains In or Out words on the left. 