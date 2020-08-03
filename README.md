# SSRS_report_user_change_password_more_6_months

0. You need to add the linked server ADSI to the root of the forest 
1. Replace LDAP://domain.corp and LDAP://subdomain1.domain.corp and LDAP://subdomain2.domain.corp to your domain and subdomain name.
2. Replace <Value>subdomain1</Value> and <Value>subdomain2</Value> to your subdomain name
3. Replace <ParameterValue>
            <Value>domain</Value>
            <Label>domain</Label>
          </ParameterValue> to your domain name
4. Replace   <rd:ReportServerUrl>http://mssql.domain.corp/ReportServer</rd:ReportServerUrl> to your report server URL
