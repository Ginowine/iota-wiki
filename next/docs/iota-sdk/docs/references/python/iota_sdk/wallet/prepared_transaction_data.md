---
sidebar_label: prepared_transaction_data
title: iota_sdk.wallet.prepared_transaction_data
---

## PreparedTransactionData Objects

```python
class PreparedTransactionData()
```

### \_\_init\_\_

```python
def __init__(account, prepared_transaction_data)
```

Helper struct for offline signing

#### Parameters

- **account**_: account object_  
   An account object used to continue building this transaction.
- **prepared_transaction_data**_: dict of prepared data_  
   The data of a prepared transaction object

## PreparedCreateTokenTransaction Objects

```python
class PreparedCreateTokenTransaction(PreparedTransactionData)
```

The function returns the token_id as a string.

**Returns**:

The token id of the PreparedCreateTokenTransaction.