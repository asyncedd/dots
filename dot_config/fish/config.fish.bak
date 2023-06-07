#!/usr/bin/env fish

# Check if starship is installed
if not type -q starship
  # Starship is not installed, so download and install it
  echo "Starship is not installed. Installing..."
  curl -sS https://starship.rs/install.sh | sh
  # Note: The --yes option automatically installs starship without prompting for confirmation
end

starship init fish | source
