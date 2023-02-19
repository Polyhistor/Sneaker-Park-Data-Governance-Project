# This is a data governance design for SneakerPark

Document to be added

Completeness - you review how much of the expected dataset is complete and what data is missing. For example, if among all the customers sign up for an account, only 20% filled in their phone number, we would say the dataset is 20% complete.

Validity - you review the data to determine if it conforms to the specified format and business rules. For example, if a text value is stored in a phone number field, it is not valid.

Consistency - you review to check if the data in multiple places or systems are consistent. For example, if the order status is ‘Canceled’ but the Cancellation date is blank, it is not consistent.

Accuracy - you review to determine if the data accurately reflects the event or object. For example, a customer asks for a return stating the product is defective, and in the return system, the return reason is blank for that order. In this case, this data is not accurate.

Uniqueness - you review whether data is duplicated in a given system or multiple systems. If data is duplicated, then the duplicates need to be eliminated.

Timeliness - you review to check if the data represent reality at a given time. For example, if the customer provided a change of address, which is not applied to the next customer bill, then the data is not timely.
