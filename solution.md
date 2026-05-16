# Solution

## Fix Issue #1
Tambahkan validasi sebelum submit:

```js
function handleSubmit() {
  if (field === '') {
    showError('Field tidak boleh kosong')
    return
  }
  submitForm()
}
```

## Status
- [x] Fixed ✅
