FROM gcr.io/google-appengine/aspnetcore:2.2
ADD ./ /app
#ENV ASPNETCORE_URLS=http://*:${PORT}
EXPOSE 8080
WORKDIR /app
ENTRYPOINT [ "dotnet", "HelloWorldAspNetCore.dll"]
