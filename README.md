# PyChain_Ledger
Building a blockchain-based ledger system with a user-friendly web interface.
---
## Technologies
This analysis leverages python 3.7 with the following packages and libraries:
* [pandas](https://github.com/pandas-dev/pandas)
* [streamlit](https://streamlit.io/)
* [hashlib](https://docs.python.org/3/library/hashlib.html)
---
## Installations
```python
pip install streamlit
```
---
## Imports
```python
from email.policy import strict
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```
---
## Usage
1) Clone repository
2) In terminal, navigate to the repository
3) Use command ```streamlit run pychain.py ``` to open the application in streamlit. 
---
## Streamlit Dashboard
![Streamlit Interface](https://user-images.githubusercontent.com/90667844/152048026-8bc7af63-c35f-49ff-9c35-62cd270b9a35.png)
---
## Use the "Validate Chain" button to validate the ledger. 
![Validate Chain](https://user-images.githubusercontent.com/90667844/152048450-85387c31-d294-4399-ad7f-c10dbf54cb86.png)
---
## Inspect a select block in the chain. 
![Block Inspector](https://user-images.githubusercontent.com/90667844/152048585-b0021227-5183-46a2-96c9-2c8d6512845e.png)

---
## Contributors
[Noah Beito](https://www.linkedin.com/in/noah-beito/)
---
## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)

