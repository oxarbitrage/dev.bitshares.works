## Wallet API Calls

#### Table of Contents:

- [General Calls](/core/api/wallet_api_ref.md#general-calls)
- [Wallet Calls](/core/api/wallet_api_ref.md#wallet-calls)
- [Account Calls](/core/api/wallet_api_ref.md#account-calls)
- [Trading Calls](/core/api/wallet_api_ref.md#trading-calls)
- [Asset Calls](/core/api/wallet_api_ref.md#asset-calls)
- [Governance](/core/api/wallet_api_ref.md#governance)
- [Privacy Mode](/core/api/wallet_api_ref.md#privacy-mode)
- [Blockchain Inspection](/core/api/wallet_api_ref.md#blockchain-inspection)
- [Transaction Builder](/core/api/wallet_api_ref.md#transaction-builder)

***

***\<Quick Links\>***

### General Calls

- [help](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a77ef88d6647e7021189b6b259ef66014)
- [gethelp](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a21d6b9297891d2a7317bfc3be9e6a917)
- [info](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af68da8c88a5d85ffa0bab63e0bc0a189)
- [about](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aab0ebcb387c74f6d733c32bc5e17131e)
- [network_add_nodes](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a751a4c02552be8c312efb86c3886faf0)
- [network_get_connected_peers](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a25e97582cdd7c8ff2da00c01a45661bd)

### Wallet Calls

- [is_new](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a50b7db1472e871aaed673b730fa4f375)
- [is_locked](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a128159228d6bad2a2243f05e960ceeaf)
- [lock](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a5e7950c9039f0c59e1266d6732d94e09)
- [unlock](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae16994a63cfdef1616b6b968117fd29d)
- [set_password](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a2a5d174ec4fde8633b8e962fabc00804)
- [dump_private_keys](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a98369ea6e10699066c7beb181996a219)
- [import_key](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a45e93f4a83143cb8ec6a09b67f91f4bb)
- [import_accounts](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a3e40e2e27d9b153fd411a7cc181ce39a)
- [import_account_keys](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a51d29f90e8ff286e4bd128a5191fe662)
- [import_balance](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ac70989a765d5f84ff3d8d6444a398512)
- [suggest_brain_key](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ab936e7a26d41b35cbfaf44d369d60e1d)
- [get_transaction_id](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a1aa926a58bec526fa357dda9d3ea1833)
- [get_private_key](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aaaf57550fa86bee57eddfd033d633081)
- [load_wallet_file](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae07628816935423a1fed072fc28b54f5)
- [normalize_brain_key](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a22a64652613c2e0b7bacf0bd0a031bc1)
- [save_wallet_file](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#addf3cfcb96bd878e6c850d3a961de9e6)

### Account Calls

- [list_my_accounts](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#acc5f625ee9aa8ba0685eb2a52b330b27)
- [list_accounts](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ade01cfbd19d3aa965d96ce4931880e40)
- [list_account_balances](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a36320ec4d8646bf2149bb4e383b291b5)
- [register_account](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aba1c5e3025f44273fb19e264c2b3ec2f)
- [upgrade_account](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af2145755728919d7e4aaf0f02d7c4e82)
- [create_account_with_brain_key](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ac27928f7ca6db74e0ec4aee3ff0c545e)
- [transfer](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a338fc74bb723d9c649f161b5279e41f0)
- [transfer2](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a52bd06d61575ff4cfc208d887db3d8ff)
- [whitelist_account](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aa6483d143fecb817fad3c08ee982bda0)
- [get_vesting_balances](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#abce0e5c4ae7fa1b93719a5865e3abb61)
- [withdraw_vesting](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a72d9316ead7ac6825fbcd62be81e235a)
- [get_account](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae4133a2fe8f63695385c20d327a88ff9)
- [get_account_id](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a4fced527782bb38f02f763e3163d7989)
- [get_account_history](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a30435c40b79d7a7cad036d3486902db3)
- [approve_proposal](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a4d550262671c5d2a3ca8ea76b41722ca)

### Trading Calls

- [sell_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aeb0d71a0ed4c6d05a003e48c3a0cb6d3)
- [borrow_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a289195f6aa33668056993ee3caeceb39)
- [cancel_order](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ab525bedb82547d7eafb77106fd26e251)
- [settle_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a95a3baa4b0c83c1fce14827acbbddd62)
- [get_market_history](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a10ac7af701dc6093e2fd80f359fc9f11)
- [get_limit_orders](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af7a75ea6f06b003c18aeb7b69aa9b0b2)
- [get_call_orders](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae0e30871ade749477335b014413b9b2a)
- [get_settle_orders](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af534b945b3c12255bcefc969387cedf1)

### Asset Calls

- [list_assets](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ade01cfbd19d3aa965d96ce4931880e40)
- [create_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae3028048916580695639fee8e9d815be)
- [update_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a6c2a57593b39390b286efeecca2702d6)
- [update_bitasset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aebe4459f45a748739595939d60b95b6b)
- [update_asset_feed_producers](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a0ce4b8d15724a5f0d2e94a83288945cd)
- [publish_asset_feed](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ad7f049ecc3f83a80c6f27ec4f1a47beb)
- [issue_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ac4ff8075641a7469265122ff9a66e30e)
- [get_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a12dcc7308bd4277d83f62ebcdbe51596)
- [get_bitasset_data](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a8e08fddb57e5eff66e703d4cf376bb15)
- [fund_asset_fee_pool](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a207a4b4afe0cac8c7f797025eb08854e)
- [reserve_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a6c6316f69afc3b8b78b669381fd96159)
- [global_settle_asset](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ad35610a05a5f4cf0d70fd4d6e8f99937)

### Governance

- [create_committee_member](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ad0c4d2890ab300fc2388bbe26bf15559)
- [get_witness](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a28f755aa12dca82f6e2e948cac014dcb)
- [get_committee_member](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af7db75896d9b2b2f4c4585172eb7d4e4)
- [list_witnesses](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae0cb01b3d7db811587ee51fa1e6c7e51)
- [list_committee_members](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ab08449f00d6b4147787b23afa7aa6af6)
- [create_witness](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a73d443a0961938c685d29277a0e4830f)
- [update_witness](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a8246cdc35c58a9776a011505684d66b8)
- [create_worker](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a85d25eaf8c6f749420e93fad46bc79cb)
- [update_worker_votes](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a4af1e9b3a5d70e1b7c5fde6a519cbd24)
- [vote_for_committee_member](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a9c2be055bd282ff68da3f3ce0f6b95fb)
- [vote_for_witness](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a00370237863a234e2418f191ce006d0c)
- [set_voting_proxy](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a444fd5cc7709e481be463393f78a2253)
- [set_desired_witness_and_committee_member_count](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a2d6765231f3bf9180ad64c5be085ba60)
- [propose_parameter_change](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a2238d380c7d5f2361533f31d996964b2)
- [propose_fee_change](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a9716675c16f6bc9c35371e8f2b28ada4)

### Privacy Mode

- [set_key_label](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af23b7d760f581179282c5113945ec725)
- [get_key_label](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a5af9cfcd4a7cba2eeb34c001c44b8b7f)
- [get_public_key](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a5a19ea70c6ed3ca720c4b335f0f2c1a5)
- [get_blind_accounts](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a725e456a4ca23ae210a22092dd5fe972)
- [get_my_blind_accounts](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a2d4ef36783314e156e6747379faebd3f)
- [get_blind_balances](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a3d11320f5123684b2855685021372d08)
- [create_blind_account](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a85d711119140bbe2ff73599baee48866)
- [transfer_to_blind](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a6209fb37844e23c339c959a7afe996df)
- [transfer_from_blind](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a8b38899a509b43720d344172323d2069)
- [blind_transfer](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a85e46a0471d5f9ae0ea122a70a7ce335)
- [blind_history](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a5ff47c6fd55fb231cf5b5a5fe36354b2)
- [receive_blind_transfer](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aed63fa0d4cbf06a4810e436482f5d5ea)

### Blockchain Inspection

- [get_block](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a16ade564115023fe9c2e4f88f0d3ddc5)
- [get_account_count](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ae921c3738042e2720652b8e037f1eac4)
- [get_global_properties](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a9f44d453c99ffc99bbd99caa9e065a95)
- [get_dynamic_global_properties](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aaa8f1ab2e2e5fe7a414ada5375e14566)
- [get_object](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a12d4903dfb4f111e7aff4ca03c1c526d)

### Transaction Builder

- [begin_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a796a8e4cd719edcf5e2c6d2d2cb8b3d7)
- [add_operation_to_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ab5cd568be3fd1c283e0ed2c1fd3c5469)
- [replace_operation_in_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ad8cc33d09f58920917736d46ef73d05e)
- [set_fees_on_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a5013c612e234e0169a9953c8ee9ce898)
- [preview_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a52d1cc372fd10bc659402400d527d215)
- [sign_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aaadd5bace87a5db813c3bd78ef1e8529)
- [propose_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#acd0cbe740362f4b83f3b97f9192039f6)
- [propose_builder_transaction2](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#ad33bc4056cefd13bca5d74f4cc0c017f)
- [remove_builder_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a92c1c80c0f7b7176d35a5a910ed7e7f5)
- [serialize_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#aa63666820114bf95165324cf5d22782f)
- [sign_transaction](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#a4c2cfac7553688e32fa64b6f4464142a)
- [get_prototype_operation](https://bitshares.org/doxygen/classgraphene_1_1wallet_1_1wallet__api.html#af52e5370f7895cb69d5f38427a11dbaf)

****
