# Auto-Assignment API Documentation


## Endpoints

### Get google merchant feed setup
- **URL**: `api/crm/settings`
- **Method**: GET
- **Headers**: 
  - `Authorization`: `Bearer <token>`
- **Responses**:
  - **200 OK**:
    ```json
    response 1
    {
    	"result": {
    		"id": 1,
    		"user_id": 36,
    		"mail_settings": {
    			"mode": 0,
    			"reroute": 0
    		},
    		"reminder_time": 8,
    		"autoresponder": 1,
    		"captcha": 1,
    		"auto_assign_lead": {
    			"active": true,
    			"priority": false,
    			"randomly": true,
    			"salespersons_priority": [
    				{
    					"id": 0,
    					"status": true,
    					"sources": [
    						{
    							"id": 1,
    							"source": "website",
    							"status": true
    						},
    						{
    							"id": 2966,
    							"source": "ebay",
    							"status": false
    						},
    						{
    							"id": 1144,
    							"source": "FB",
    							"status": true
    						}
    					],
    					"last_name": "A A",
    					"first_name": "ibrahim"
    				},
    				{
    					"id": 1096,
    					"status": true,
    					"sources": [
    						{
    							"id": 1,
    							"source": "website",
    							"status": false
    						},
    						{
    							"id": 2966,
    							"source": "ebay",
    							"status": true
    						},
    						{
    							"id": 1144,
    							"source": "FB",
    							"status": true
    						}
    					],
    					"last_name": "T T",
    					"first_name": "Achraf"
    				},
    				{
    					"id": 1097,
    					"status": true,
    					"sources": [
    						{
    							"id": 1,
    							"source": "website",
    							"status": true
    						},
    						{
    							"id": 2966,
    							"source": "ebay",
    							"status": false
    						},
    						{
    							"id": 1144,
    							"source": "FB",
    							"status": true
    						}
    					],
    					"last_name": "M M",
    					"first_name": "Ahmed"
    				}
    			],
    			"salespersons_randomly": [
    				{
    					"id": 0,
    					"status": true,
    					"last_name": "A A",
    					"first_name": "ibrahim"
    				},
    				{
    					"id": 1096,
    					"status": true,
    					"last_name": "T T",
    					"first_name": "Achraf"
    				},
    				{
    					"id": 1097,
    					"status": true,
    					"last_name": "M M",
    					"first_name": "Ahmed"
    				}
    			]
    		},
    		"next_lead_assignee_id": null,
    		"auto_assign_task": {
    			"active": true,
    			"priority": true,
    			"randomly": false,
    			"salespersons_priority": [
    				{
    					"id": 0,
    					"status": true,
    					"last_name": null,
    					"first_name": "Owner"
    				},
    				{
    					"id": 1,
    					"status": true,
    					"last_name": null,
    					"first_name": "kokoko"
    				},
    				{
    					"id": 2,
    					"status": true,
    					"last_name": null,
    					"first_name": "bobobo"
    				}
    			],
    			"salespersons_randomly": [
    				{
    					"id": 0,
    					"status": true,
    					"last_name": null,
    					"first_name": "Owner"
    				}
    			]
    		},
    		"next_task_assignee_id": null,
    		"qualification": 0,
    		"qualification_options": null,
    		"is_archive_enabled": 0,
    		"from_name": null,
    		"calendar_identifier": null,
    		"default_color": null,
    		"dealership_address": null,
    		"logo_url": null,
    		"created_at": "2024-12-27T08:10:52.000000Z",
    		"updated_at": "2024-12-30T10:20:44.000000Z"
    	},
    	"status": {
    		"code": 200,
    		"type": "success",
    		"message": "success"
    	}
    }
    response 2
    {
    	"result": null,
    	"status": {
    		"code": 200,
    		"type": "success",
    		"message": "success"
    	}
    }
    ```
    