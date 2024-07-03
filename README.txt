This is a new solution to managing standard .py files that are needed for many projects. We can put them in a central location and then import them via the file path so we can keep these 'master' copies up to date in one place.


you can use these matser files by first appending the sys path and then importing
import sys
sys.path.append(r"<PATH TO THIS FOLDER>")
from master_logger import *


This is good because it means key infrustructure can be kept up to date and added to seperate from each project. though you can copy and paste these files into projects if you want to edit a unique version of these
