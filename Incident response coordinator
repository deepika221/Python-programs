class Incident:
    def __init__(self, id, desc, status, coord):
        self.id = id
        self.desc = desc
        self.status = status
        self.coord = coord

class IncidentManager:
    def __init__(self):
        self.incidents = {}
        self.next_id = 1

    def add_incident(self, desc, status, coord):
        incident = Incident(self.next_id, desc, status, coord)
        self.incidents[self.next_id] = incident
        self.next_id += 1
        print(f"Added: ID {incident.id}")

    def view_incidents(self):
        for incident in self.incidents.values():
            print(f"[ID: {incident.id}] {incident.desc} | Status: {incident.status} | Coordinator: {incident.coord}")

def main():
    manager = IncidentManager()
    while True:
        choice = input("\n1. Add 2. View 3. Exit: ")
        if choice == '1':
            desc = input("Description: ")
            status = input("Status: ")
            coord = input("Coordinator: ")
            manager.add_incident(desc, status, coord)
        elif choice == '2':
            manager.view_incidents()
        elif choice == '3':
            break

if __name__ == "__main__":
    main()
