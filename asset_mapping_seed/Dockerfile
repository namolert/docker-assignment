# You don't need to modify the following 
FROM mongo:5.0

WORKDIR /var/dmongo
COPY . /var/dmongo
CMD mongoimport --host asset_mapping -d user -c userProfile --drop --type json --file /var/dmongo/profile_asset.json --jsonArray
