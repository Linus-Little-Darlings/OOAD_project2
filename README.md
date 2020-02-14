# OOAD_project2, The Friendly Zoo pt. 2

**Team Members**: Jake Andrus and Zora Watters <br/>
**Language and Environment**:We used Python as our language and Jupyter Notebook to develop, then converted into a .py file! <br/>
**Running code**: Our main method is located outside the Zookeeper class! You can run the .py or the .ipynb <br/>
**Assumptions**: Animals all sleep, eat, and roam, make noise, and wake up. <br/>
We have classes for each species and Animal type, but not for the middle men like, "feline" or "canine" - the reason for this is because our strategy pattern handles this sort of behavior. We also have classes for Zoo, Zookeeper, and ZooAnnouncer. Only a few functions are overridden in the animal classes themselves, and usually just to randomize behavior. <br/>
This article helped us understand strategy in Python: https://medium.com/@sheikhsajid/design-patterns-in-python-part-1-the-strategy-pattern-54b24897233e
