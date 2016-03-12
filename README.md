# edu

echo "# edu" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/iconductor7/edu.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/iconductor7/edu.git
git push -u origin master



echo "# edu" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/iconductor7/edu.git
git push -u origin master
git remote add origin git@github.com:iconductor7/edu.git


    def handle_read(self):
        data = self.recv(8192)
        if data:
            if data == 'close':
                self.close()
            else:
                self.send(data)
                
 git remote add origin https://github.com/iconductor7/e
du.git



class EchoHandler(asyncore.dispatcher_with_send):                               
  def handler_read(self):                                                       
    data=self.recv(1024)                                                        
    if  data:                                                                   
      if data=='close':                                                         
        self.close()                                                            
      else:                                                                     
        self.send(data)                                                        $
                           
