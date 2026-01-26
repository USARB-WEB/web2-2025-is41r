Parent module
/api/v1/parent/{id}

Child module
/api/v1/child/{id}


Task 1:
De realizat un nou endpoiunt care returneaza toti copii unui parinte dupa ID-ul parintelui
/api/v1/parent/{id}/children


Exemple:
/api/v1/brand/{id}
/api/v1/brand/{id}/products

/api/v1/factory/{id}
/api/v1/factory/{id}/assembly-lines

/api/v1/airlines/{id}
/api/v1/airlines/{id}/flight-routes

Task 2:
De realizat filtrarea, de afisat toti copii unu parinte dupa ID-ul parintelui
/api/v1/children?parent_id={id}

Exemple:
/api/v1/flight-routes?airline_id={id}
