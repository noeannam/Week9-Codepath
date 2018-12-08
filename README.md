# Week9-Codepath
I spent about **20+** hours on this project.
# Honeypot Deployed
The honeypot that I deployed was Dionaea over HTTP.

# Issues I Encountered
The main thing I really struggled with was getting access to the mhm admin console. It took a long time to figure out what was actually wrong with the console. I soon discovered, after many hours of research, that I was missing the tcp 80 port. I feel like the instructions could have been a little more clear as to what needs to be done. It was a lot of guess and check. I spent a lot of time on this project and it was frustrating at times.
# Summary of the Data Collected
The first thing I did was download all of the gcloud information. It took awhile to ensure that gcloud was installed properly. Once I installed everything correctly, I was able to start using the Google Cloud Platform. I found the GCP to be very interesting and that is where I created my admin vm and my honeypot. I followed the steps through until I encountered the error in Milestone 2. Everything ran well until I typed in sudo ./install.sh. I had to then go into the install_hpfeeds.sh file and change HurricaneLabs to Couozu. Once I changed this, I was able to compelete Milestone 2. I then moved on to Milestone 3, where I was able to create the honeypot. Everything went smoothly through Milestone 3, but once I got to Milestone 4, I encountered the same error over and over again. Everytime I went to access the admin counsel, it said that it could not connect to the server. I checked the firewall rules and realized it might be an issue with one of the ports. I did some research and discovered that a lot of people were struggling with the same thing in the class, as well as online. 
