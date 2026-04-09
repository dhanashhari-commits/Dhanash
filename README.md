# Dhanash
Banking System
def __init__(self, customer_id, name, email, phone):
        self.customer_id = customer_id
        self.name = name
        self.email = email
        self.phone = phone

def display_info(self):
        """Return customer details as a string."""
        return (
            f"Customer ID: {self.customer_id}, Name: {self.name}, "
            f"Email: {self.email}, Phone: {self.phone}"
        )

def update_email(self, new_email):
        """Update customer email."""
        self.email = new_email

def update_phone(self, new_phone):
        """Update customer phone number."""
        self.phone = new_phone

def to_csv_row(self):
        """Convert customer data to CSV row format."""
        return [self.customer_id, self.name, self.email, self.phone]
