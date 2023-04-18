- # data for hfnc
  template:: hfnc-data
  template-including-parent:: false
	- type:: hfnc-data
	  hfnc-flow:: 
	  hfnc-fio2:: 
	  endpoints:: 
	  machine:: 
	  procedure:: 
	  sedation::
- {{query (property :type "hfnc-data")}}
  query-table:: true
  query-properties:: [:page :hfnc-flow :hfnc-fio2 :endpoints :machine :sedation :procedure]
-