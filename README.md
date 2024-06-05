# VenuitiFarmCollectorRepository


Overview
FarmCollector is a system designed to collect and report on data provided by farmers about their planting and harvesting activities. The system will have two main endpoints: one for recording planted data and one for recording harvested data. Reports comparing expected vs. actual harvests will be available through a web page for every season.

Application Structure

Models

Farm
Season
Crop
Planted
Harvested
Repositories

FarmRepository
SeasonRepository
CropRepository
PlantedRepository
HarvestedRepository
Services

FarmService
SeasonService
CropService
PlantedService
HarvestedService
ReportService
Controllers

PlantedController
HarvestedController
ReportController
DTOs

PlantDTO
CropDTO
FarmDTO
HarvestDTO
ReportDTO
Unit Tests

PlantedControllerTest
HarvestedControllerTest
ReportControllerTest
HTML Views

report.html
Database Configuration

H2 Database setup
