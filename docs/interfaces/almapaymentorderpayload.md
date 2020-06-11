[@permettezmoideconstruire/alma-client](../globals.md) › [AlmaPaymentOrderPayload](almapaymentorderpayload.md)

# Interface: AlmaPaymentOrderPayload ‹**CDT, CODT**›

## Type parameters

▪ **CDT**: *object*

▪ **CODT**: *object*

## Hierarchy

* **AlmaPaymentOrderPayload**

## Index

### Properties

* [customer](almapaymentorderpayload.md#optional-customer)
* [order](almapaymentorderpayload.md#optional-order)
* [orders](almapaymentorderpayload.md#optional-orders)
* [payment](almapaymentorderpayload.md#payment)

## Properties

### `Optional` customer

• **customer**? : *[AlmaCustomerPayload](../globals.md#almacustomerpayload)*

*Defined in [src/types/payment.ts:60](https://github.com/permettez-moi-de-construire/alma-client/blob/b80dcbf/src/types/payment.ts#L60)*

___

### `Optional` order

• **order**? : *[AlmaOrderPayload](../globals.md#almaorderpayload)‹CODT›*

*Defined in [src/types/payment.ts:58](https://github.com/permettez-moi-de-construire/alma-client/blob/b80dcbf/src/types/payment.ts#L58)*

___

### `Optional` orders

• **orders**? : *[AlmaOrderPayload](../globals.md#almaorderpayload)‹CODT›[]*

*Defined in [src/types/payment.ts:59](https://github.com/permettez-moi-de-construire/alma-client/blob/b80dcbf/src/types/payment.ts#L59)*

___

###  payment

• **payment**: *[AlmaPaymentPayload](../globals.md#almapaymentpayload)‹CDT›*

*Defined in [src/types/payment.ts:61](https://github.com/permettez-moi-de-construire/alma-client/blob/b80dcbf/src/types/payment.ts#L61)*