# Tips about AWS 

- Pay attention to Free Tier. Billing is not real-time and you should stop services ASAP.
- C++ SDK is a low level SDK and its docs are not adequate. Python is preferred for most use. 

## ElastiCache

- All of EC2, Lambda and ElastiCache should be set with available Security Group. As a bad example, set them with allowing all traffic.