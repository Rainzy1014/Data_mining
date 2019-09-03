# Introduction of Web Data Mining
## World Wide Web
The World Wide Web is officially defined as a “wide-area hypermedia in-formation retrieval initiative aiming to give universal access to a large uni-verse  of  documents.” The  Web's  implementation  follows  a  standard  client-server  model. The  operation  of  the  Web  relies  on  the  structure  of  its  hypertextdocuments. Hypertext allows Web page authors to link their documents to other related documents residing on computers anywhere in the world.
## History of the Web and the Internet
1989, the web was invented by Tim Berners-Lee  
1990, Berners-Lee  re-circulated  a  proposal  and  received  the  support  to  begin the work. The proposal essentially outlined a distributed hyper-text system, which is the basic architecture of the Web.  
1993, Marc  Andreesen and his team released the first "Mosaic for  X"  graphical  Web  browser  for  UNIX.   
mid-1994, Jim Clark collaborated with Marc  Andreessen, and they  founded the company Mosaic Communica-tions. Within a few months, the Netscape browser was released to the public, which started the explosive growth of the Web.  
1995, The Internet Explorer from Microsoft entered the market   
From  1995  to  2001,  the  growth  of  the  Web  boomed.
## Web Data Mining
the characteristics of the web:
1. The  amount  of  data/information  on  the  Web  is  huge  and  still  growing. 
2. Data  of  all  types  exist  on  the  Web
3. Information  on  the  Web  is  heterogeneous.
4. A  significant  amount  of  information  on  the  Web  is  linked. 
5. The  information  on  the  Web  is  noisy.  
6. The  Web  is  also  about  services. 
7. The  Web  is  dynamic. 
8. The Web is a virtual society. 
### Data Mining
Data  mining  is  also  called  knowledge  discovery  in  databases(KDD).    
Data  mining  tasks:
* supervised   learning 
* unsupervised   learning
* association rule mining（关联规则挖掘）
* sequential pattern mining（序列模式挖掘）
   
 A  data  mining  application  usually  starts  with  an  understanding  of  the  application  domain  by  data  analysts (data  miners),  who  then  identify  suitable data sources and the target data.       
Data mining can be performed, which is usually carried out in three main steps:   
* Pre-processing:  The  raw  data  may need to be cleaned in order to remove noises or abnormalities.  The  data  may  also  be  too  large  and/or  involve  many  irrelevant attributes, which call for data reduction through sampling and attribute  selection. 
* Data mining: The processed data is then fed to a data mining algorithm which will produce patterns or knowledge. 
* Post-processing:  In  many  applications,  not  all  discovered  patterns  are  useful.  This  step  identifies  those  useful  ones  for  applications.    
With the growth of the Web and   text   documents,   Web   mining   and   text   mining   are   becoming   increasingly important and popular. 
### Web Mining 
Web  mining  aims  to  discover  useful  information  or  knowledge  from  the  **Webhyperlink structure, page content, and usage data**.  
Based  on  the  primary  kinds  of  data  used  in  the  mining  process,  Web  mining  tasks  can  be  categorized  into  three  types:  **Web  structure  mining,  Web  content  mining and Web usage mining.**    
* Web  structure  mining：Web  structure  mining  discovers  useful  knowl-edge  from  hyperlinks  (or  links  for  short),  which  represent  the  structure  of  the  Web.    
    e.g. from  the  links,  we  can  discover  important  Web  pages,  which,  incidentally,  is  a  key  technology  used  in  search  en-gines. 
* Web  content  mining： eb content mining extracts or mines useful in-formation or knowledge from Web page contents.  
    e.g. automatically  classify  and  cluster  Web  pages  according  to  their  topics.  **These tasks are similar to those in traditional data mining.**   

* Web usage mining: Web  usage  mining  refers  to  the  discovery  of  user  access patterns from Web usage logs, which record every click made by each user.  
    e.g. One of  the  key  issues  in  Web  usage  mining  is  the  pre-processing  of  click-stream data in usage logs in order to produce the right data for mining. 
  
The Web mining process is similar to the data mining process. The difference is usually in the **data collection**. In traditional data mining, the data is often already collected and stored in a data warehouse. For Web mining, data  collection  can  be  a  substantial  task,  especially  for  **Web  structure**  and  **content  mining**,  which  involves  crawling  a  large  number  of  target  Web  pages.
