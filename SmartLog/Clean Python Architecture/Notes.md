

Prereq:
 ![[Pasted image 20230524015008.png|400]]



- Value of this is if we replace the web framework with CLI then it does not take a lot of time

![[Pasted image 20230524015604.png|400]]
- Entities contain classes
- Use Cases contain business rules
- Gateways do not contain business rules. Example is where database interface would live
- External system has access to everything inside
- 
![[Pasted image 20230524020207.png|400]]







https://github.com/pycabook/rentomatic/tree/second-edition-top/tests

# 3.2. Domain models
## Test Driven Development

Remember to create an empty file __init__.py in every subdirectory of tests/ that you create, in  
this case tests/domain/__init__.py.





# 3.4. Use cases


tests/use_case
```python

import pytest  
import uuid  
from unittest import mock  
from rentomatic.domain.room import Room  
from rentomatic.use_cases.room_list import room_list_use_case  
@pytest.fixture  
def domain_rooms():  
	room_1 = Room(  
	code=uuid.uuid4(),  
	size=215,  
	price=39,  
	longitude=-0.09998975,  
	latitude=51.75436293,  
	)  
	room_2 = Room(  
	code=uuid.uuid4(),  
	size=405,  
	price=66,  
	longitude=0.18228006,  
	latitude=51.74640997,  
	)  
	room_3 = Room(  
	code=uuid.uuid4(),  
	size=56,  
	price=60,  
	longitude=0.27891577,  
	latitude=51.45994069,  
	)  
	room_4 = Room(  
	code=uuid.uuid4(),  
	size=93,  
	price=48,  
	longitude=0.33894476,  
	latitude=51.39916678,  
	)  
	return [room_1, room_2, room_3, room_4]


def test_room_list_without_parameters(domain_rooms):  
	repo = mock.Mock()  
	repo.list.return_value = domain_rooms  
	result = room_list_use_case(repo)  
	repo.list.assert_called_with()  
	assert result == domain_rooms
```

# 3.5. The storage system- External System

