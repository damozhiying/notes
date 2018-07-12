
## close index
    POST /etc-sh-index/_close                                    v

## update index default analyzer  
    PUT /etc-sh-index/_settings
    {
                "analysis": {
                    "analyzer": {
                       "default":{
                          "type":"ik_max_word"
                       }
                    }
                }
      
     
    }


## re-open index
    POST /etc-sh-index/_open
