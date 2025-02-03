---
description: Creating and closing accounts
---

# Accounts

Accounts are the only structure on the registry that can hold and handle PECs, and each company can set up as many accounts as it needs. There are four types of accounts you may set up, based on how you will use the registry (more on types of accounts here and actions an account can take here):

* **Producer Holding Account:** You are a CFE generator. This account can be issued and can transfer PECs.
* **General Holding Account:** You are a electricity user or intermediary. This account can transfer and retire PECs.
* **Energy Carrier Holding Account:** You are a energy carrier such as electricity storage operator or hydrogen producer. This account can be issued, transfer, and can retire PECs.

## Creating an account <a href="#creating-an-account" id="creating-an-account"></a>

A company representative can create a new account by going to the Accounts section of the platform and clicking "Create an account" on the top right corner of your screen. Each type of account has its own creation process, but all include:

1. **Choose an account name**: names do not need to be unique and may be changed in the future.
2. **Designate how many signatures** will be required for your account to perform an action. If you enter "2" then your account will require two Account Representatives to approve an action (e.g., to transfer a PEC) before it can be initiated. The number of signatures may be changed at any time by a company representative.
3. **Add account representatives**: you may designate yourself as an account representative and invite others by email to join your account as an account representative. Each account representative you add has a specific "signing right" that dictates if they can **initiate** actions, **approve** actions, do both, or do neither (that is, users with "read only" access may only review an account but not perform any actions on it).

{% hint style="info" %}
If your account requires more signatures than it has active account representatives with signing rights, then your account will be temporarily blocked (more on statuses below).
{% endhint %}

## Account status <a href="#account-status" id="account-status"></a>

An account can be in one of four statuses:

1. **Active:** account is fully functional.
2. **Rejected:** account creation was denied by the registry administrator
3. **Blocked:** account was temporarily put into a read-only status. A blocked account cannot be used to issue or manage PECs
4. **Closed:** a company representative chose to discontinue the account. A closed account is permanently in a "read-only" state.

{% hint style="info" %}
Even if an account is blocked, account representatives retain "read-only" access to account holdings.
{% endhint %}

## Closing an account <a href="#closing-an-account" id="closing-an-account"></a>

A Company Representative can close an account by clicking on the three dots at the end of your account in the "Accounts" section. Accounts cannot be closed if they contain any active PECs.
