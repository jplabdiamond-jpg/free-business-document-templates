# INVOICE

**{{ your_business_name }}**
{{ your_address_line_1 }}
{{ your_address_line_2 }}
{{ your_email }} · {{ your_phone }}
{{ your_tax_id_label }}: {{ your_tax_id }}

---

**Invoice #:** {{ invoice_number }}
**Issue date:** {{ issue_date }}
**Due date:** {{ due_date }}

**Bill to:**
{{ customer_name }}
{{ customer_address }}
{{ customer_email }}

---

| # | Description | Qty | Unit price | Amount |
|---|-------------|----:|-----------:|-------:|
| 1 | {{ item_1_description }} | {{ qty_1 }} | {{ unit_price_1 }} | {{ amount_1 }} |
| 2 | {{ item_2_description }} | {{ qty_2 }} | {{ unit_price_2 }} | {{ amount_2 }} |
| 3 | {{ item_3_description }} | {{ qty_3 }} | {{ unit_price_3 }} | {{ amount_3 }} |

| | |
|---|---:|
| **Subtotal** | {{ subtotal }} |
| **{{ tax_label }} ({{ tax_rate }}%)** | {{ tax_amount }} |
| **Total due** | **{{ currency }}{{ total }}** |

---

**Payment details**
{{ payment_instructions }}
(e.g. bank name, account name, account number / IBAN, or a payment link)

**Notes:** {{ notes }}

---
*Need this as a finished PDF with the tax calculated for you? Generate it free at https://free-bizdocs.com/en/invoice*
