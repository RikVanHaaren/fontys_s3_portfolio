# Ethics
After researching what exactly ethics entailed, I looked at my project to see if there are any ethical issues with it. This is where I came to the point: “Save user log files”. I really liked logging all the data I used and storing it in a log file so that when something went wrong in my application I could easily trace back exactly what went wrong here .

In the “ACM Code of Ethics and Professional Conduct, 1.6 Respect and Privacy”. Is it about that you have to take responsibility and have respect with the collection of data and this also specifically on personal information. So I started searching the internet for what falls under this. I came across the EU's General Data Protection Regulation (GDPR). This is a legal system that is valid in Europe and is about what personal data you can and cannot collect. Personal data means according to [Article 4 (1)](https://www.termsfeed.com/blog/gdpr-articles/#Article_4_Definitions), means information that can be used to identify a person.

*Scenario*
In een van de projecten log ik alle IP adressen samen met het verzoek wat ze sturen. Ik doe dit omdat ik wil voorkomen dat gebruikers die geen toegang hebben tot bepaalde poorten per ongeluk toegang krijgen tot gevoelige bestanden. Omdat je een persoon kan identificeren met een dynamic IP adres wordt dit beschouwd als persoonlijke data.

In the first view, I was not aware of this because I tried to properly maintain my application and prevent any attacks by saving it. After these studies, I've started to look at this very differently and I personally don't think it's ethical to store all this data from users. In addition to the ethical aspect, according to the law, I also did not handle this information properly. 
Before I will put this online, I will have to draw up a privacy policy stating that I store this data. An alternative is to remove this IP address for now and ask the service provider if they want to provide this IP address when I notice that something is not right.

This reflection helped me to understand which values and norms play a role in this situation. This has given me more insight into the difficult choices of which data to store and how to deal with it. As a result, I am better aligned with the users of the application. It is also better to take this into account in the future because I did not know at first that I was dealing with this wrong.

Sources:
https://www.termsfeed.com/blog/gdpr-log-data/#Personal_Data
https://www.acm.org/code-of-ethics
https://www.academia.edu/22298452/Ethical_dilemma_Log_files_what_to_save_and_how_to_handle_them
