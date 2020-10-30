# Poc_v1

New version of insurance system. 
This project customize the client's insurance based on their needs. 

Business requirements and limitation:  
1.This system should support up to 500,000 product.  
2.Web portal should support desired growth for an increase in operations up to 50% in 5 years.  
3.Support transaction in the future.  

System requirements Summary:  
1. Account Management.   
    -- individual accounts, agency accounts.  
2. Order Management.   
    -- including shipping.  
    -- dynamically route orders(based on the business rule)
3. Personalization.   
    -- Visulization tools of summary. 
4. Live Chat.    
    -- corporate with health organization, online doctor.
5. Product Catalog.    
6. Search.   
    -- require quick mathch *ElasticSearch.
7. Promotions.   
    -- best price guarantee based on their individual/ corporate entities.
8. Insurance Comparison.    
9. Checkout/ Payment.   
   -- third party (ex. palpay, credit card)


Technical Requirement:  
1.back-end and front-end seperation.  
2.back-end technical stack: SpringBoot + OAuth + Oracle + RabbitMQ. 
3.front-end technical stack: Angular. 
