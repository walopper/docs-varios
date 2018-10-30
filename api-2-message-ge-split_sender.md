## /message/list

#### Request all campaign by parent

    {
        "user_key": "4b0c5b37ef58df1e510f999",
        "type": "split_sender_all",
        "spid": "99999"
    }
```sid``` is the campaign ID of any campaign in the group.
    
#### Request split_sender campaigns
    {
    	"user_key": "4b0c5b37ef58df1e510f999",
    	"type": "split_sender"
    }
    
#### Request regular campaigns
    {
    	"user_key": "4b0c5b37ef58df1e510f999",
    	"type": "campaign"
    }
    
#### Response
    {
        "total_results": 5,
        "returned_results": 5,
        "messages": [
            {...campaginData},
            {...campaginData},
            {...campaginData},
            {...campaginData},
            {...campaginData}
        ]
    }
