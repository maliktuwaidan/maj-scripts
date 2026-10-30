run hardening script

bash -c "$(curl -fsSL https://raw.githubusercontent.com/maliktuwaidan/maj-scripts/main/rocky-linux/10/hardening/standard-hardening.sh)"

--

run hardening validation script

sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/maliktuwaidan/maj-hardening/main/rocky-linux/10/standard-hardening-validation.sh)"
