# photon
class Photon:
    def __init__(self, wavelength_nm, energy_eV):
        self.wavelength_nm = wavelength_nm
        self.energy_eV = energy_eV

    def display_info(self):
        print("Photon Information:")
        print(f"Wavelength: {self.wavelength_nm} nm")
        print(f"Energy: {self.energy_eV} eV")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Photon class
    photon = Photon(wavelength_nm=500, energy_eV=2.48)

    # Displaying information about the photon
    photon.display_info()
