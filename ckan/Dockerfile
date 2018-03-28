FROM openknowledge/ckan-base:2.7

MAINTAINER Terje Christensen <terje@christensen.no>


# Install any extensions needed by your CKAN instance
# (Make sure to add the plugins to CKAN__PLUGINS in the .env file)
# For instance:
#RUN pip install -e git+https://github.com/ckan/ckanext-pages.git#egg=ckanext-pages && \
#    pip install -e git+https://github.com/ckan/ckanext-dcat.git@v0.0.6#egg=ckanext-dcat && \
#    pip install -r https://raw.githubusercontent.com/ckan/ckanext-dcat/v0.0.6/requirements.txt

# Install the extension(s) you wrote for your own project
# RUN pip install -e git+https://github.com/your-org/ckanext-your-extension.git@v1.0.0#egg=ckanext-your-extension


#Terchris: Adding urbalurba extensions
RUN pip install -e git+https://github.com/ckan/ckanext-pages.git#egg=ckanext-pages && \
    pip install -e git+https://github.com/conwetlab/ckanext-datarequests.git#egg=ckanext-datarequests && \
    pip install -e git+https://github.com/OpenGov-OpenData/ckanext-showcase.git#egg=ckanext-showcase && \
    pip install -e git+http://github.com/ckan/ckanext-harvest.git#egg=ckanext-harvest && \
    pip install -r https://raw.githubusercontent.com/ckan/ckanext-harvest/master/pip-requirements.txt && \
    pip install -e git+https://github.com/ckan/ckanext-dcat.git#egg=ckanext-dcat && \
    pip install -r https://raw.githubusercontent.com/ckan/ckanext-dcat/master/requirements.txt && \
    pip install -e git+https://github.com/TkTech/ckanext-cloudstorage.git#egg=ckanext-cloudstorage && \
    pip install -e git+https://github.com/terchris/ckanext-utbalurba_theme.git#egg=ckanext-utbalurba_theme 
    
