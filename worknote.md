#Meeting 20170331
##Items to discuss
1. a list of people that will be potential stakeholders of the project; this should include any professor / staff member / others such as students or alums who are going to use the system.
    
    I or some else will need to go through the list to collect system requirements by talking to them or via other ways.

2. very likely we will go to cloud; better to use iu's services.

    Olga or other people who can represents GIS should apply for those service accounts:
    * RDC MySQL account;
    * Any IU web service that supports PHP(5.6.4 or higher)
    * the disk space of the web service
        * will there be many multimedia data, such as hi-res images, videos, audios, and ?
        * if this is the case, can we utilize YouTube for such resources?
        
3. if the system is limited within GIS, how are we going to host it?
4. potential system size:
    * number of records in database
    * number of users
        * number of roles / Access Control role.
        * or what access privileges we should have?
        
5. desired functionalities:
    * use a form to collect requirement:
        * name
        * needed functionalities (multiple input fields)
        * necessity (Must / Nice-To-Have / Just Saying)
        
        | < Qiwen Zhu: ~email~ > | requirement | level of necessity|
        | ------------- |:-------------:| -----:|
        |1|filter out all GIS alum that graduated in a specified year|must|
        |2|export filtered results to .csv / MS excel file|Nice|
        |3|tell me which alum like  apple best|Just saying
