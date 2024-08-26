# Purchase_Order_Bot
The Purchase Order Bot automates creating purchase orders in the Apptivo system. It begins with a Dispatcher bot that extracts data from Data\PurchaseOrders.xlsx and loads transactions into the UiPath Orchestrator Queue. The Performer bot then processes these transactions, and updates the purchase order  in the Excel file,
