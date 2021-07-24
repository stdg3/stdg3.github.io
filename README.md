# Alex V.
Citizen G3

class CitizenG3(People, Engineer, Coder, MotoRider):
"""One of the high voltage coder... ish"""
    def __init__(self):
        self.CREED = "just program the resistor"
        self.JOY = super.engineering() + super().code() + super().ride()
