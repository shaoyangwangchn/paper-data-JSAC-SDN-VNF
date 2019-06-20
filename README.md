<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
# paper_data

## Detailed meaning

### COST266_data_t.xlsx
**Column**  

         A: Serial number of nodes  

         B: Abscissa of nodes  
        
         C: Ordinate of nodes
        
         E: Serial number of links  $$(u,v)$$
        
         F: Serial number of source nodes $$s$$
        
         G: Serial number of destination nodes  $$t$$
        
         H: Unit routing cost of links (Real data)  $$c_{\left(u,v\right)}^{B^{e}}$$
        
         I/J: Unused in this paper
        
### VNF_set.xlsx
**Column**  

         A: The required storage space of 10 different VNF category  $$f_{l}^{\mathrm{m}}\left(r^{\mathrm{b}}\right)$$

         B: The required processing bandwidth factor of 10 different VNF category $$f_{l}^{\mathrm{B^{v}}}\left(r^{\mathrm{b}}\right)$$
        
         C: The required compute resource factor of 10 different VNF category  $$f_{l}^{\mathrm{c}}\left(r^{\mathrm{b}}\right)$$
        
         D: The processing delay factor of 10 different VNF category   $$f_{l}^{\mathrm{pv}}\left(r^{\mathrm{b}}\right)$$

### Resource_compute.xlsx
**Column**  

         A: The total compute resources of different nodes  $$C_{n}$$
           
### Resource_handle.xlsx
**Column**  

         A: The total processing bandwidth resources of different nodes  $$B_{n}^{v}$$
         
 ### Resource_storage.xlsx
**Column**  

         A: The total storage space resources of different nodes $$M_{n}$$       
         
### Resource_link.xlsx
**Column**  means the serial number of nodes
  
**Row**  means the 10 different VNF category

Each element means the bandwidth resources of different links  $$B_{\left(u,v\right)}^{e}$$

         
### Delay_handle.xlsx
**Column**  

         A: The processing delay of different nodes  $$d_{n}^{\mathrm{pn},i}$$       
   
### Delay_trans.xlsx
**Transmission delay matrix** 37 rows and 37 columns 

Each element means the transmission delay of different links $$d_{\left(u,v\right)}^{\mathrm{t},i}$$         
         
### Cost_compute.xlsx
**Column**  

         A: The cost factor of unit compute resource for different nodes $$c_{n}^{c}$$
         
### Cost_deploy.xlsx
**Column**  means the serial number of nodes
  
**Row**  means the 10 different VNF category

Each element means the deployment cost factor of different VNFs at different nodes $$c_{j,n}^{d,i}$$

### Cost_handle.xlsx
**Column**  

         A: The cost factor of unit processing bandwidth resource for different nodes $$c_{n}^{B^{v}}$$
         
### Cost_rout.xlsx
**Routing cost matrix** 37 rows and 37 columns 

Each element means the routing cost factor of different links for unit demand rate $$c_{\left(u,v\right)}^{B^{e}}$$
           
### Cost_handle.xlsx
**Column**  

         A: The cost factor of unit storage resource for different nodes $$c_{n}^{m}$$
         

       
