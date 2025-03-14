Move-Item -Path Files1 -Destination .\EvenFolder                                                                                                                                         
Move-Item -Path Files1 -Destination EvenFolder                                                                                                                                           
cd .\FolderTest1                                                                                                                                                                         
Move-Item -Path Files1 -Destination EvenFolder1                                                                                                                                          
mv "File1" C:\EvenFolder                                                                                                                                                                 
Get-ChildItem                                                                                                                                                                            
Get-ChildItem -Path C:\EvenFolder                                                                                                                                                        
mv "File3" et "File5" C:\EvenFolder                                                                                                                                                      
mv "File3""File5" C:\EvenFolder                                                                                                                                                          
mv "File3" "File5" C:\EvenFolder                                                                                                                                                         
mv "File3" C:\EvenFolder                                                                                                                                                                 
mv "File5" C:\EvenFolder                                                                                                                                                                 
mv "File2" C:\EvenFolder                                                                                                                                                                 
mv "File4" C:\EvenFolder                                                                                                                                                                 
cd                                                                                                                                                                                       
cd ..                                                                                                                                                                                    
cd .\EvenFolder                                                                                                                                                                          
Get-ChildItem -Path C:\EvenFolder                                                                                                                                                        
mv "File" C:\OddFolder                                                                                                                                                                   
mv "File4" C:\OddFolder                                                                                                                                                                  
mv "File4" C:\EvenFolder                                                                                                                                                                 
mv "File1" C:\OddFolder                                                                                                                                                                  
mv "File3" C:\OddFolder                                                                                                                                                                  
mv "File5" C:\OddFolder                                                                                                                                                                  
cd ..                                                                                                                                                                                    
cd .\OddFolder                                                                                                                                                                           
mv "File4" C:\EvenFolder                                                                                                                                                                 
Get-ChildItem -Path C:\OddFolder                                                                                                                                                         
cd ..                                                                                                                                                                                    
cd .\EvenFolder                                                                                                                                                                          
Get-ChildItem -Path C:\EvenFolder                                                                                                                                                        
Get-History > historique.txt                                                                                                                                                             
Get-ChildItem -Path *Folder* -Recurse > listing.txt                                                                                                                                      
