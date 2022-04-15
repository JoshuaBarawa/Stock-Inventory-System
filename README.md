# End-Points
* v1/account/ register/ [name='register-user']
* v1/account/ register-clerk/ [name='register-clerk']
* v1/account/ login/ [name='login-user']
* v1/account/ logout/ [name='logout-user']
* v1/account/ email-verify/<str:token_id>/ [name='email-verify']
* v1/account/ view-clerks/ [name='view-clerks']
* v1/account/ view-admins/ [name='view-admins']
* v1/account/ inactivate/<str:id>/ [name='inactivate-clerk']
* v1/account/ activate/<str:id>/ [name='activate-clerk']
* v1/account/ delete/<str:id>/ [name='delete-clerk']


* v1/account/
* v1/product/ add/ [name='add-product']
* v1/product/ status/paid/ [name='paid-products']
* v1/product/ status/unpaid/ [name='unpaid-products']
* v1/product/ status/change/<str:id>/ [name='change-payment-status']
* v1/product/ request/ [name='request-product']
* v1/product/ view-requests/ [name='view-requests']
* v1/product/ view-requests/approved [name='approved-requests']
* v1/product/ view-requests/n-approved [name='not-approved-requests']
* v1/product/ request/approve/<str:id>/ [name='approve-request']
* v1/product/ request/decline/<str:id>/ [name='decline-request']