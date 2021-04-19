Here we have 4 Customer sites:
Customer A and Customer B each has 2 sites.
what i did here was to connect these customers sites to each other using MPLS L3VPN.

configuretions :
Core MPLS : OSPF 1

IGP to customers :
EIGRP Named mode (CUSTOMER-A and CUSTOMER-B)

iBGP peering between : 
PE-R1 <-> PE-R6

CUSTOMER-A: 
Route Distinguisher : 10:10
Route Target : 100:100


CUSTOMER-B: 
Route Distinguisher : 20:20
Route Target : 200:200
