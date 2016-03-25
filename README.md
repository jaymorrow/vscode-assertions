# Node.js Assertion Snippets

This extension contains code snippets for Node.js assertions for [Visual Studio Code](https://code.visualstudio.com/).

## Installation

* Launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type `install extension`.
* Search for `assertion snippets`

## Snippets

### afa - [assert.fail](https://nodejs.org/api/assert.html#assert_assert_fail_actual_expected_message_operator)
    assert.fail(${1:actual}, ${2:expected}, ${3:message}, ${4:operator});

### ass - [assert](https://nodejs.org/api/assert.html#assert_assert_value_message_assert_ok_value_message)
    assert(${1:actual}${2:, ${3:message}});

### aok - [assert.ok](https://nodejs.org/api/assert.html#assert_assert_value_message_assert_ok_value_message)
    assert.ok(${1:actual}${2:, ${3:message}});

### aeq - [assert.equal](https://nodejs.org/api/assert.html#assert_assert_equal_actual_expected_message)
    assert.equal(${1:actual}, ${2:expected}${3:, ${4:message}});

### ane - [assert.notEqual](https://nodejs.org/api/assert.html#assert_assert_notequal_actual_expected_message)
    assert.notEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### ade - [assert.deepEqual](https://nodejs.org/api/assert.html#assert_assert_deepequal_actual_expected_message)
    assert.deepEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### ande - [assert.notDeepEqual](https://nodejs.org/api/assert.html#assert_assert_notdeepequal_actual_expected_message)
    assert.notDeepEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### ase - [assert.strictEqual](https://nodejs.org/api/assert.html#assert_assert_strictequal_actual_expected_message)
    assert.strictEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### anse - [assert.notStrictEqual](https://nodejs.org/api/assert.html#assert_assert_notstrictequal_actual_expected_message)
    assert.notStrictEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### adse - [assert.deepStrictEqual](https://nodejs.org/api/assert.html#assert_assert_deepstrictequal_actual_expected_message)
    assert.deepStrictEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### andse - [assert.notDeepStrictEqual](https://nodejs.org/api/assert.html#assert_assert_notdeepstrictequal_actual_expected_message)
    assert.notDeepStrictEqual(${1:actual}, ${2:expected}${3:, ${4:message}});

### ath - [assert.throws](https://nodejs.org/api/assert.html#assert_assert_throws_block_error_message)
    assert.throws(${1:block}${2:, ${3:error}}${4:, ${5:message}});

### adnt - [assert.doesNotThrow](https://nodejs.org/api/assert.html#assert_assert_doesnotthrow_block_error_message)
    assert.doesNotThrow(${1:block}${2:, ${3:error}}${4:, ${5:message}});

### aif - [assert.ifError](https://nodejs.org/api/assert.html#assert_assert_iferror_value)
    assert.ifError(${1:value});
