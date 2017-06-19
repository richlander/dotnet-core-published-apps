FROM microsoft/dotnet-nightly:2-runtime-stretch
WORKDIR app
COPY bin/release/netcoreapp2.0/publish .
ENTRYPOINT ["dotnet","2.0.dll"]
