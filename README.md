BUNDLE 1
Exercise 1

C:\Users\Ejitade Isaac\Downloads\cmder                                                                  
λ mkdir Gym-Git-Exercise-Solutions                                                                      
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder                                                                  
λ git init Gym-Git-Exercise-Solutions                                                                   
Initialized empty Git repository in C:/Users/Ejitade Isaac/Downloads/cmder/Gym-Git-Exercise-Solutions/.g
it/                                                                                                     
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder                                                                  
λ cd Gym-Git-Exercise-Solutions                                                                         
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(master)                               
λ git branch -m master main                                                                             
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ cat > README.md                                                                                       
                                                   BUNDLE 1                                             
Exercise 1                                                                                              
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ git add -A                                                                                            
warning: LF will be replaced by CRLF in README.md.                                                      
The file will have its original line endings in your working directory                                  
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ git commit -m "Created a readme file"                                                                 
[main (root-commit) ca18913] Created a readme file                                                      
 1 file changed, 2 insertions(+)                                                                        
 create mode 100644 README.md                                                                           
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ cat ~/.ssh/id_rsa.pub                                                                                 
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCybrs7J8MVAxoBzkxJ7GWquNpoQ6A1TEJOHTeSeFduSpwFi4BMta8QFTMlfK/183Tx
AeS/UNKyHkoOQ1n/WzUdJhZf7Di3Sf+ewkhiJc9umsCohwVYbpazK+pQgBBg5qHGfxoPqjEdyNWcyrECugfCbqtbvugs+f4PxmZG8iSD
Nb0jKSjcBLh3Fyr9yoAwOrhOUe+9fkehRhzpZidqUDe7xr+HdOe2hiL1jerdZ9KpZg/mtoRIXRsdT/YBI+tS9Du1pEvkGTTdLz+IwhkE
heA4zm2kYzJn0GMmjRBGXKwRA32WacPb1Gsa4bAH5xlmNIpgairo3UrO7Vfn2SNqxfJWmVYskv1s1v+eq32hH/PNN2YIeo5lGqAU673i
mxrytpIdK7DXuEyi3c5UgwchY9RxdL1O975ZgaGMZpzuE3dNx9c3Bxj2VPsrp6RAH0Rtu3e0JcbHVwbeGIX4c+eCPHtpqEIrfm93jOX6
ll0kWsqNVCwTqmUHfg/Cz16RzxoqssM= demilade@LAPTOP-DI2M6NDB                                               
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ git remote add orgin git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git                      
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git                                  
Enumerating objects: 3, done.                                                                           
Counting objects: 100% (3/3), done.                                                                     
Writing objects: 100% (3/3), 240 bytes | 80.00 KiB/s, done.                                             
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0                                                    
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git                                              
 * [new branch]      main -> main                                                                       
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ git branch dev                                                                                        
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)                                 
λ git checkout dev                                                                                      
Switched to branch 'dev'                                                                                
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(dev)                                  
λ git branch test                                                                                       
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(dev)                                  
λ git branch -d test                                                                                    
Deleted branch test (was ca18913).                                                                      
                                                                                                        
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(dev)                                  
λ git branch                                                                                            
* dev                                                                                                   
  main                                                                                                  
